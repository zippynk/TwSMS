#TwSMS

[![Join the chat at https://gitter.im/zippynk/TwSMS](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/zippynk/TwSMS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


TwSMS is a Unix command written in Python for sending and receiving text messages via a Twilio account. It uses the Twilio Python Library, which is licensed under the MIT License by a separate party (and is not included - it needs to be installed separately).


#Usage

sms login [ACCOUNT SID] [AUTH TOKEN] [PHONE NUMBER]

sms logout

sms send [PHONE NUMBER TO SEND TO] [MESSAGE BODY]

sms view-messages [OPTIONAL: PHONE NUMBER TO SEE MESSAGES FOR]

sms help

#License

TwSMS is written by zippynk on bitbucket.org and is licensed under the Mozilla Public License, Version 2.0.

It is available online at https://bitbucket.org/zippynk/twsms.

Official Notice:

  This Source Code Form is subject to the terms of the Mozilla Public

  License, v. 2.0. If a copy of the MPL was not distributed with this

  file, You can obtain one at http://mozilla.org/MPL/2.0/.