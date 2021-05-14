# bedrock-emotes
A collection of Bedrock Edition emote UUIDs found through gophertunnel

# How do you get these emote IDs?
Emotes are sent by the client using the Emote packet and are broadcasted to other players with the same UUID. These UUIDs are mapped to emote animations client side. However, we can steal these emote IDs by using a gophertunnel client. Once we steal these emote IDs, we upload them to this repository using the bedrock-emotes account and mark them as unidentified, after which users of bedrock-emotes can identify these emotes with a proper image, description, and name.

bedrock-emotes gets the emotes from all featured servers. If the bedrock-emote client gets disconnected from a featured server, it reconnects. The client also automatically moves slightly to avoid anti AFK measures.

# What's the point of grabbing emote IDs?
Emote IDs can be useful for developers trying to incorporate expression into things like NPCs, storytelling, and more. A public collection of all known emotes can be very helpful to many developers.
