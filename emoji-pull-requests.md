# Emojis in Pull Request Comments
I feel that Pull Requests (PRs) can be very impersonal, and it is often hard to gauge
how important a change is to a reviewer.

This can cause interesting conflicts between team members e.g. when one person's

> style: parentheses

is interpreted as "this must be changed", when in fact it is just a personal preference.

To work around this, I use emoji as a prefix for PR comments, to indicate how urgent it is to address this change.

## Explanation of Emoji
| Emoji  | Severity                                                                                                                                   |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| ❓     | Request for clarification; this might be an issue, but I'm not sure.<br>Or: I've not understood what this code does, could you explain?    |
| 💬     | Note. Nothing to change here.                                                                                                              |
| 💡     | Coding tip!                                                                                                                                |
| 👏     | Highlighting some great code!                                                                                                              |
| 🤷🤷‍♂️🤷‍♀️ | Minor issue, or suggestion.<br>Fine to ignore as this is not important.<br>Could be a style comment, a personal preference, or just a pointer. |
| 🐛     | Bug: This needs to be addressed before the PR is merged.                                                                                   |
| 💣     | Architectural issue: A discussion should be had about the approach in this PR.                                                             |
