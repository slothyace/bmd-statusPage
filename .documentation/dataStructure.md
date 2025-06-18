# Data Structure

The data that is sent to the `/raw` endpoint are as follows:

```
{
  prjName: "<str>",
  data:[
    {
      timestamp: "<ISO 8601>", 
      cpu: "<num, in %>", 
      memory: "<num, in MB>", 
      counts: {
        guild: "<num, int>",
        users: "<num, int>"
      }
    },
    ...
  ],
  updInterval: <num, int>,
  uptime: <num, in seconds>,
  logs:[
    {
      msg: "<str>",
      timestamp: "<ISO 8601>",
      type: "<str>"
    },
    ...
  ],
  commands: {
    slashCmd: <num, int>,
    textCmd: <num, int>,
    msgCmd: <num, int>,
    userCmd: <num, int>,
    msgCntCmd: <num, int>,
    anyMsgCmd: <num, int>,
    event: <num, int>
  },
  versions: {
    node: "<Node Version>",
    oceanic: "<Oceanic.js Version>"
  }
}