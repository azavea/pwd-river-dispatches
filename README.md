# pwd-river-dispatches
Application developed in partnership with the Fairmount Waterworks, under Azavea's PWD contract. The "Dispatches from the River" exhibit  will introduce users, first, to the concept that the watershed is being monitored through these data points, and, second, to a few key learnings that show how collecting this data has helped us understand and manage our water resources more effectively. This activity will focus on five key measures: temperature, turbidity, salinity, Dissolved Oxygen, and pH.

### Requirements

 * Node v4.5+

### Getting Started

Unzip the original package from PWD into a folder in your system. Then run:

```
./scripts/setup $SOURCE_DIR
```

where `$SOURCE_DIR` is the path of the unzipped directory on your local.

#### Development

Run the server using

```
./scripts/server
```

### Ports

| Port | Service |
| --- | --- |
| [9000](http://localhost:9000) | Node Development Server |

### Scripts

| Name | Description |
| --- | --- |
| `server` | Run a node development server |
| `setup` | Install NPM dependencies |
