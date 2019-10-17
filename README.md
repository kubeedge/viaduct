# Viaduct
The viaduct is a bridge that carries a road across a valley，the valley is the gap between cloud and edge and the bridge is the connection across the gap

# Overview
Viaduct use the protobuf3.0 to serialize message that defined in beehive and provide  
apis for connection and message operations

By now, Viaduct has supported websocket(gorilla websocket) and quic(quic-go) as the basic transport protocol

## Where does it come from?
 `viaduct` is synced from https://github.com/kubeedge/kubeedge/tree/master/staging/src/github.com/kubeedge/viaduct.
Code changes are made in that location, merged into `github.com/kubeedge/kubeedge` and later synced here.
