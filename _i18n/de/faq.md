# Häufig gestellte Fragen

*   [Kontoeinstellungen](#kontoeinstellungen)
*   [Starte eine Unterhaltung](#starte-eine-Unterhaltung)
*   [Chateinstellungen](#chateinstellungen)
*   [Mit anderen Chat-Systemen verknüpfen](#mit-anderen-Chat-Systemen-verknüpfen)
*   [Fehlerbehandlung](#fehlerbehandlung)
*   [About FluffyChat](#about-fluffychat)

## Kontoeinstellungen

#### Wie kann ich mein Passwort zurücksetzen?

Du musst eine E-mail-Adresse mit deinem Konto verknüpft haben. Das kann in den Kontoeinstellungen gemacht werden. Falls du keine E-mail-Adresse verknüpft hast, musst du den Support deines Homeservers kontaktieren. ([Was ist ein Homeserver?](#Whatisahomeserver))

[Klicke hier, um dein Passwort zurückzusetzen](https://www.ubports.chat/#/forgot_password)

#### How can I create a new account?

1.  If you are already logged in in FluffyChat then go to the settings and tab on "Logout" at the bottom.
2.  Choose a new username and make sure that "Create an account" is checked.
3.  If you want to create an account on another homeserver than the default (ubports.chat), go to the top left menu and change the homeserver. ([What is a homeserver?](#Whatisahomeserver))
4.  Go to "Log In" and choose a new password.

#### How can I log in my old account?

1.  If you are already logged in in FluffyChat then go to the settings and tab on "Logout" at the bottom.
2.  Enter the username or your Matrix ID of your old account. ([What is a Matrix ID?](#WhatisaMatrixID)) If you don't remember your username or Matrix ID but you remember the phone number connected with your account, then you can just enter any username and enter the correct phone number in the next step. The username will be automatically found.
3.  (Optional) Enter the phone number of your old account.
4.  If your old account is not on the default homeserver (ubports.chat), go to the top left menu and change the homeserver. ([What is a homeserver?](#Whatisahomeserver))
5.  Make sure that "Create an account" is **not** checked.
6.  Go to "Log In" and enter your password. ([Password forgotten?](#HowcanIresetmypassword))

#### What is a Matrix ID?

Your Matrix ID is your unique identifier in the Matrix network. It is a combination of your username and your homeserver. ([What is a homeserver?](#Whatisahomeserver))  
The format of a Matrix ID is simple: @username:homeserver. For example, if your username is "alice" and your homeserver is "homeserver.abc", then your Matrix ID is: @alice:homeserver.abc

#### What is a homeserver?

Matrix is a federated network of homeservers. What does this mean? There is no centralized "FluffyChat server" but there are multiple homeservers you can use. You are free to pick the homeserver you want. Like the email all users from all homeservers can communicate with eachother. There is a default homeserver on FluffyChat named "https://ubports.chat". You are able to host your own homeserver. [Click here for a guide how to start](https://matrix.org/docs/guides/installing-synapse).

#### What is an identity server?

Users in Matrix are identified internally via their Matrix ID. However, existing 3rd party ID (3PID) namespaces such as email addresses or phone numbers should be used publicly to identify Matrix users, at least for invitation purposes. A Matrix "Identity" describes both the user ID and any other existing IDs from third party namespaces linked to their account.  
Matrix users can link third-party IDs (3PIDs) to their user ID. Linking 3PIDs creates a mapping from a 3PID to a user ID. This mapping can then be used by Matrix users in order to discover the MXIDs of their contacts. In order to ensure that the mapping from 3PID to user ID is genuine, the intention is for a globally federated cluster of trusted "Identity Servers" (IS) be used to verify the 3PID and persist and replicate the mappings. Usage of an IS is not required in order for a client application to be part of the Matrix ecosystem. However, without one clients will not be able to look up user IDs using 3PIDs.

## Starte eine Unterhaltung

#### How can I start a new chat?

1.  Go to the "+" button at the start page or swipe up from the bottom on phones.
2.  Choose your contacts you want to invite to your new chat. You can at least invite zero contacts.
3.  If you don't find a contact, you can [add them by their phone number](#HowcanIaddcontactsbytheirphonenumber) or enter their Matrix ID in the search field. ([What is a Matrix ID?](#WhatisaMatrixID))
4.  Go to "Create Chat"
5.  If you want to create a direct chat with one contact, just select only one contact or touch the avatar and go to "Start direct chat".

#### How can I join a public chat?

A public chat has one or more public addresses called aliases. They always start with '#' and end with ':homeserver.abc'. For example: [#fluffychat:matrix.org](fluffychat://#fluffychat:matrix.org). Just click on the link to participate in the chat or enter an alias in the search field at the start page of FluffyChat.

#### How can I join a community?

A public chat has one or more public addresses called aliases. They always start with '+' and end with ':homeserver.abc'. For example: [+ubports\_community:matrix.org](fluffychat://+ubports_community:matrix.org). Just click on the link to see all chats associated with this community. For more features, visit the [desktop web app](https://www.ubports.chat).

#### How can I add contacts by their phone number?

1.  Go to the "+" button at the start page or swipe up from the bottom on phones.
2.  Go to the add contact button at the top left.
3.  Choose your address book app.
4.  Select the contact you want to add or select all contacts and confirm.
5.  FluffyChat will search for these contacts in the identity server. ([What is an identity server?](#Whatisanidentityserver))

#### Which /commands are available?

*   `/me` (Will send msgtype: m.emote) Displays an action.
*   `/whisper` (Will send msgtype: m.fluffychat.whisper) The message text will be very small
*   `/roar` (Will send msgtype: m.fluffychat.roar) The message text will be very large, bold and in capital letters
*   `/shrug` Puts ¯\\(ツ)/¯ at the start of the message

## Chateinstellungen

#### How can I kick or ban a user from a chat?

You need the permission to kick or ban a user from a chat.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Find the user you want to kick or ban and swipe the user list item to the right.
4.  Click on the kick or the ban button and confirm

#### How can I change the user permissions in a chat?

You need the permission to change the user permissions.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Find the user you want to kick or ban and swipe the user list item to the left.
4.  Click on the desired user permission button and confirm

#### How can I change the chat topic and description?

You need the permission to change the chat topic and description.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Click on the top right edit button and enter the desired chat topic and/or description

#### How can I edit the chat privacy settings?

You need the permission to edit the chat privacy settings.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Go to "Privacy and security"
4.  Toggle or untoggle the desired options and edit the user permission options

#### What are chat aliases and how can I edit them?

Chat aliases are public chat addresses which can be used to join a chat. You need the chat permissions to change them.

1.  Go to the chat
2.  Go to "Chat infos" in the top right menu
3.  Go to "Privacy and security"
4.  Toggle or untoggle the desired options and edit the user permission options

#### How can I send animated stickers with Giphy?

1.  Start a new chat with [@neb\_giphy:​matrix.org](fluffychat://@neb_giphy:​matrix.org).
2.  Search for gifs by typing: '!giphy KEYWORD'
3.  Add an animated sticker by clicking on the sticker and add it to your local sticker collection by clicking on the "+" on the rop right.

## Mit anderen Chat-Systemen verknüpfen

#### What is Matrix?

Matrix is an open standard for interoperable, decentralised, real-time communication over IP. It can be used to power Instant Messaging, VoIP/WebRTC signalling, Internet of Things communication - or anywhere you need a standard HTTP API for publishing and subscribing to data whilst tracking the conversation history.

#### How can I enter a XMPP multi-user chat?

The easiest way currently is to use the bridge on matrix.org.  
Every XMPP multi-user chat has a Jabber identifier (JID) with the format: `chatname@chat.server.abc`  
The chatname is the **local** part and the chat.server.abc is the **server** part. You can enter this chat by entering the Matrix public room: `#_xmpp_server_local:matrix.org` ([How can I join a public chat?](#HowcanIjoinapublicchat))  
For the given example this would be: `#_xmpp_chat.server.abc_chatname:matrix.org`

#### How can I enter an IRC node on Freenode?

If you want to enter the node `#chatname` on freenode you can just join the public chat: `#freenode_#chatname:matrix.org`  
Replace `#chatname` with the node you want to join and you are in.

#### How can I bridge a group chat with a Telegram group chat?

Look at the tutorial on [wayneoutthere.com](https://wayneoutthere.com/how-to-bridge-matrix-telegram/).

## Fehlerbehandlung

#### Why don't I receive push notifications?

Do you have an Ubuntu One account in the system settings?  
When you go into fluffychat -> Settings -> Notifications -> Targets: Is there a device "UbuntuPhone"?  
Have you tried to logout and login?  
Do you have the latest version of FluffyChat installed from the OpenStore?  
Have you tried to turn airplaine mode on and off again? Sometimes notifications are sent with a delay from the UBports push service (will be fixed soon) If you still have the problem, then please contact me at the room: [#fluffychat:matrix.org](fluffychat://#fluffychat:matrix.org)

#### Why can't I connect with port 8448?

Sorry! confused On port 8448 the most homeservers use a different ssl certificate, which causes an error. Currently the xmlhttprequest in QML does not allow those certificates.

#### Why can't I connect with self signed certificate?

The same problem... I recommend you to use a letsencrypt certificate.

## About FluffyChat

#### How is FluffyChat founded?

FluffyChat is funded by the community. You can support FluffyChat on [Patreon](https://www.patreon.com/krillechritzelius) or [Liberapay](https://liberapay.com/KrilleChritzelius)
