# Current things

- Work out the auth
- Test read and write of the bot

## Some considerations

- Not doing everything in JS server because teammate handling LLM part wants to use Python and does not want to deal with JS server stuff. Setting up a REST API to make the separation of responsibilities between teammates easier.
- Use Fastify instead of Express because it is more modern, faster, and provides better TS support.