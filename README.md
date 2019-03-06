# Jan

Jan is a web server with high performance.

## History

The project was first used in **2016**.
Which is still being developed and rebuilt.

### First version 0.1

```
int main(int argc, char *argv[]);
void httpSet(int code);

void bodyPush(const char *content);
void bodyPushLength(const char *content,int length);

void serverPush(const char *content);
void serverPushLength(const char *content,int length);

void headerSet(const char *name,const char *value);
void headerDone();

void stringSet(char *source,const char* input);
int stringLength(const char *string);
int stringCompare(const char *string1,const char *string2);
```
