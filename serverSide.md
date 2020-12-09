
void run()
User addUser()
void removeUser(User user)
void sendNickname(User user)
void broadcastMessages(String msg, User userSender)
void broadcastAllUsers()
void unicastMessages(String msg, User userSender, String user)
String validate(String nickname)
void getThreadId()


class UserHandler
void run()
void publicSend(String message)
void privateSend(String message)

class User
User(Socket client, String name)
PrintStream getOutStream()
InputStream getInputStream()
String getNickname()
String toString()

