# demo



We cannot implicitly convert type int or string to enum.
Therefore we need to convert it explicitly by using a cast.
So we can assign it in either ways:
MessageType = Enum.Parse("Transaction),
OR
MessageType = (SystemMessageType)2,
