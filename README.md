# Digital Garden

A content authoring tool with bidirectional links and other garden features.

## Commands

### Setting the garden path

```shell
GARDEN_PATH=~/github/my-digital-garden garden write
garden -p ~/github/my-digital-garden write
garden --garden_path ~/github/my-digital-garden write
```
## Write

Open a new file to write in our digital garden. Since we don't necessarily know what we want to title what we're writing, we'll leave the title as optional and ask the user for it later if they don't provide it upfront. 

```shell
garden write
gardn write -t "Some Title"
```
