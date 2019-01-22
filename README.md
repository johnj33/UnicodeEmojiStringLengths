# UnicodeEmojiStringLengths
|Test| Unicode.net (LetterCount)| Unicode.net (codepointCount)| StringInfo| Regex|
|---|---|---|---|---|
|`Empty string`| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:|
|a| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:|
|🐳| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:|
|🇫🇮|:negative_squared_cross_mark:| :negative_squared_cross_mark:| :negative_squared_cross_mark:| :heavy_check_mark:|
|🇫🇮🐳|:negative_squared_cross_mark:| :negative_squared_cross_mark:| :negative_squared_cross_mark:| :heavy_check_mark:|
|This is a test message containing 2 emojis this is the first one😘 and the second is the following💏 this string should be exactly 160 characters long because aya| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:|
