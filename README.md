# gmod_instances

This System creates multiple Instances of the Map by preventing the server to network the entities which are not in the same instance as the player.
That means the Entities still exist on the Server, but not for the Client.

Player can choose on which Instance they want to play.

2 Player who are not in the same Instance can't
- see each other
- hear each other
- see Props/Entities which the other oneSpawns

Every Entity which is not in the same Instance than the Player wont be networked to the Player so he cant interact with it.


Complete Show Off can be seen here:

https://www.youtube.com/watch?v=33GMKenR2-0


For example, 2 or more TTT Rounds could be played parallel on one Server with multiple Instances (all rounds would be on the same Map, no server can load 2 maps at the same time).

This would just need some edits on the TTT gamemode.
