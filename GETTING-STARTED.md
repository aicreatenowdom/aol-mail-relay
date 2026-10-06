# AOL Mail Relay: automatically forward new AOL Inbox mail

## Set up scheduled AOL mail forwarding on Windows

1. Download the signed installer from the [official product page](https://aicreatenow.com/aolrelay.html) and install the application.
2. Configure your AOL mailbox using an **AOL app-specific password**.
3. Enter the destination email address and select the checking interval.
4. Activate forwarding. This establishes the fresh-mail boundary for eligible new Inbox messages.
5. Keep the Windows computer awake and connected. Review dashboard status and logs, and use the immediate-check control when you want to check the configuration.

## Understand which messages are forwarded

The relay checks AOL through authenticated IMAP and sends eligible messages through authenticated AOL SMTP. Normal inline content and attachments are forwarded while the originals and their read/unread status remain in AOL.

It handles new **Inbox** mail after activation. It is not a mailbox migration tool: earlier messages remain excluded even if later marked unread or moved into the Inbox.

## Common questions

**Does the dashboard need to stay open?** No. Scheduled checks can run without it, but Windows must be powered on, awake and connected.

**Is delivery instant?** Checks follow the selected interval, from 30 minutes to 24 hours. Mail received while the computer is off or asleep remains in AOL and may be processed when the relay runs again.

**Why has forwarding paused?** Review the dashboard and log. A backlog of more than 125 eligible unprocessed messages triggers a protective pause; failure cooldown and retry behavior can also affect timing.

**Can I try it first?** The complete application has a three-day trial. Current one-computer lifetime licensing and delivery details are on the official product page.

Never include the AOL app password in a public issue or screenshot. Send diagnostic questions privately to [support](SUPPORT.md). This independent Windows application is not an AOL-hosted forwarding feature.

[Back to product overview](README.md) · [Support](SUPPORT.md)
