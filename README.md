SiriServerSMSPlugin
===================

A plugin for SiriSeverCore for SMS messaging. Handles reading, sending, replying.

Usage
=====

Make messages directory in the server plugin directory
copy __init__.py to the messages directory
add "messages" on its own line in the server plugin.conf file.

Commands
========

Message Checking -> Say "Check my messages"
	Siri will respond with the number of new messages you have

Message Reading -> Say "Read my messages"
	Siri will read your new messages, and prompt you to reply or read it again
	you can also say "Done" to move on to the next new message, or finish reading messages

NOTICE
=====

Usage of this plugin requires you use the modifications to SiriServerCore in pull request here: https://github.com/Eichhoernchen/SiriServerCore/pull/75
or you can use the version in my repo, which is clean plus the additions in the pull request.
