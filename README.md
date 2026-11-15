# nexy-mail

Email for Nexy apps: templates written as `.nexy` components, sent through SMTP or an email API,
previewed in the browser during development.

## What it covers

| Area | First version |
|---|---|
| Templates | `.nexy` components with props, rendered to HTML that email clients accept, plus a text version |
| Transports | SMTP, Resend, Postmark, Amazon SES, and a console transport for tests |
| Development | every sent email caught and shown at a dev page, nothing leaves the machine |
| Sending | sent in the background through [nexy-jobs](https://github.com/NexyPy/nexy-jobs) when it is installed |
| Testing | an outbox fixture to assert what was sent |

## Status

Design phase. Nothing is published yet.

## License

MIT
