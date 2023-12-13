# UAdvancedActorLoggerBPLibrary: Blueprint Function Documentation


# LogActorComponents
Purpose: Logs the components of a specified actor.
Parameters:
AActor* Actor: The actor whose components are to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
Description: This function iterates through all components of the given actor and logs their names into a file.
# LogSystemTime
Purpose: Logs the current system time.
Parameters:
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the current system time in a standard format.
# LogActorQuat
Purpose: Logs the quaternion rotation of the specified actor.
Parameters:
AActor* Actor: The actor whose quaternion rotation is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Retrieves and logs the quaternion rotation of the actor.
# LogActorLocation
Purpose: Logs the location of the specified actor.
Parameters:
AActor* Actor: The actor whose location is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the X, Y, and Z coordinates of the actor's location.
# LogActorRotation
Purpose: Logs the rotation of the specified actor.
Parameters:
AActor* Actor: The actor whose rotation is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the roll, pitch, and yaw values of the actor's rotation.
# LogActorScale
Purpose: Logs the scale of the specified actor.
Parameters:
AActor* Actor: The actor whose scale is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
ScaleType::Type Scale: The type of scale to log (ActorScale, ActorScale3D, ActorRelativeScale3D).
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Depending on the ScaleType, this function logs the actor's scale, 3D scale, or relative 3D scale.
# LogActorVelocity
Purpose: Logs the velocity of the specified actor.
Parameters:
AActor* Actor: The actor whose velocity is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the X, Y, and Z components of the actor's velocity.
# LogActorLifeSpan
Purpose: Logs the lifespan of the specified actor.
Parameters:
AActor* Actor: The actor whose lifespan is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the remaining lifespan of the actor.
# LogIsHiddenState
Purpose: Logs the hidden state of the specified actor.
Parameters:
AActor* Actor: The actor whose hidden state is to be logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs whether the actor is hidden or not.
# LogIntegerToBinary

Purpose: Converts an integer to its binary representation and logs it.
Parameters: 
int32& Value: The integer value to be converted to binary.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Converts the given integer to a binary string and logs it.
# LogMessage

Purpose: Logs a custom message.
Parameters: 
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
FString& Message: The message to log.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Logs the provided message to the specified file.
# LogDistanceBetweenActorsToFile
Purpose: Logs the distance between two actors.
Parameters: 
AActor* First: The first actor.
AActor* Second: The second actor.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Calculates and logs the distance between two specified actors.
# LogActorToFile

Purpose: Logs various properties of an actor based on the provided settings.
Parameters: 
AActor* Actor: The actor to log.
FActorLoggerSettings& ActorLoggerSettings: Settings that determine which properties of the actor are logged.
FString& FilePath: The file path for the log file.
FString& FileName: The name of the log file.
bool ClearAndWrite: If true, the log file is cleared before writing; otherwise, appends to the file.
Description: Based on the settings, this function logs selected properties like location, rotation, scale, velocity, etc., of the specified actor.





