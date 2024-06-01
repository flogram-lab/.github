Semi-public ecosystems aggregate large amounts of user-generated content. For instance, Google does not index content from millions of users in Telegram Messenger's public channels.

Accessing this data from external systems presents challenges due to the non-HTTP protocol and potential _technical_ limitations imposed by the official client code for reading or searching data.

**Wayout** is a set of microservices to enable access to telegram open information in the form of an API or URL, addressing various difficulties encountered when retrieving public channel messages from semi-public ecosystems like Telegram using native official sources (tdlib). Messages are persisted, streamed by request and have no reduntant data.

Flogram tools and server is for research purposes only.
