### 下载豆瓣红心音乐 ###

使用eyeD3对mp3打标签，对其做了一个小修改，以便能够写入中文信息，即frames.py文件第294行，将

    DEFAULT_ENCODING = LATIN1_ENCODING;
改为

    DEFAULT_ENCODING = UTF_8_ENCODING;