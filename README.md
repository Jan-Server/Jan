# Jan

Jan is a web server with high performance.

## History

The project was first used in **2016**.
Which is still being developed and rebuilt.

### First version 0.1

```c
int main(int argc, string argv[]);
void exitServer(int code);

void parseRequest();

void httpSet(int code);

void bodyPush(const string content);
void bodyPushLength(const string content,int length);

void serverPush(const string content);
void serverPushLength(const string content,int length);

void headerSet(const string name,const string value);
void headerDone();

string Int2String(int number);
int String2Int(string value);

void stringSet(string source,const char* input);
int stringLength(string string);
int stringCompare(const string string1,const string string2);
string stringReverse(string string, int length);

pid_t forkProcess();
int bindSocket(int sockfd, const struct sockaddr *addr,socklen_t addrlen);
int listenSocket(int socket,int backlog);
int closeSocket(int fildes);
int acceptSocket(int socket,struct sockaddr *restrict address,socklen_t *restrict address_len);

```
