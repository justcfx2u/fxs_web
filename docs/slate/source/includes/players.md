# Players

This endpoint retrieves all players.

url: `/fsdata/players`

## Get All Players

This gets all the players on the server.

**HTTP REQUEST**

`get /fsdata/players/`


```JSON
```
>The above command returns JSON structured like this:
```JSON
```

## Get a Specific Player

**HTTP REQUEST**

`get /fsdata/players/{net_id}`

**URL Parameters**

Parameter|Description
---------|-----------
net_id   |The player's id.

### **net_id Parameter** 

    This is the id of the player


## Actions

This performs a specific task on a player.

**HTTP REQUEST**

`get /fsdata/players/{net_id}/actions/{action}`

>The above command returns JSON structured like this:

```C#
d
```

**URL Parameters**

Parameter|Description
---|---
action|s
net_id|the player netid

###  **Action Parameter**

  Action|Description
  ---|---
  kick| Kicks the palyer.
  ban| Bans the player.
  message|Sends a message to the player.

###  **net_id Parameter** 

    This is the id of the player