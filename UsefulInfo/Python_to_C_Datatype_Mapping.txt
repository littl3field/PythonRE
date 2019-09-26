C Type                        Python Type         ctypes Type 
________________________________________________________
char                          1-character         string c_char 
wchar_t                       1-character         Unicode string c_wchar 
char                          int/long            c_byte 
char                          int/long            c_ubyte 
short                         int/long            c_short 
unsigned short                int/long            c_ushort 
int                           int/long            C_int 
unsigned int                  int/long            c_uint 
long                          int/long            c_long 
unsigned long                 int/long            c_ulong
long long                     int/long            c_longlong 
unsigned long long            int/long            c_ulonglong 
float                         float               c_float 
double                        float               c_double 
char * (NULL terminated)      string or none      c_char_p 
wchar_t * (NULL terminated)   unicode or none     c_wchar_p 
void *                        int/long or none    c_void_p
