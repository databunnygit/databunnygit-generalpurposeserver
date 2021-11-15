# General purpose management server

General purpose management server is a server software that runs on linux/windows, it creates bunch of rest api that is used by General purpose agent to connect with.

The purpose of General purpose management server is use General purpose management agent remote monitor client server status, docker container/instance status, and create and detele docker container instance remotely from General purpose management server.

The architecture is design for General purpose management server simple:

1. General purpose management agent periodically call General purpose management server rest api
2. General purpose management agent receive action from General purpose management server.
3. General purpose management agent execute action, and send back result to General purpose management server rest api

There is management UI interface available for General purpose management server to mananage clients, agent, actions, action schedules, actions running status/results.
