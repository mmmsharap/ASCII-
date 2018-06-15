
# ASCII-ХУЙ
Simple and configurable util to get ascii ХУЙ-like pattern

## Usage:
```python
import string
import random

# also u need to import hui from wherever

for i in range(5):
    width = random.randint(10, 100)
    char = random.choice(string.punctuation)

    print hui(width=width, char=char)
```
Output:

                                                 ,
                                                 ,
                                                 ,
    ,               , ,               , ,                ,,
     ,             ,   ,             ,  ,               , ,
      ,           ,     ,           ,   ,              ,  ,
       ,         ,       ,         ,    ,             ,   ,
        ,       ,         ,       ,     ,            ,    ,
         ,     ,           ,     ,      ,           ,     ,
          ,   ,             ,   ,       ,          ,      ,
           , ,               , ,        ,         ,       ,
            ,                 ,         ,        ,        ,
           , ,               ,          ,       ,         ,
          ,   ,             ,           ,      ,          ,
         ,     ,           ,            ,     ,           ,
        ,       ,         ,             ,    ,            ,
       ,         ,       ,              ,   ,             ,
      ,           ,     ,               ,  ,              ,
     ,             ,   ,                , ,               ,
    ,               , ,                 ,,                ,

                                                       ^
                                                       ^
                                                       ^
    ^                 ^ ^                 ^ ^                   ^^
     ^               ^   ^               ^  ^                  ^ ^
      ^             ^     ^             ^   ^                 ^  ^
       ^           ^       ^           ^    ^                ^   ^
        ^         ^         ^         ^     ^               ^    ^
         ^       ^           ^       ^      ^              ^     ^
          ^     ^             ^     ^       ^             ^      ^
           ^   ^               ^   ^        ^            ^       ^
            ^ ^                 ^ ^         ^           ^        ^
             ^                   ^          ^          ^         ^
            ^ ^                 ^           ^         ^          ^
           ^   ^               ^            ^        ^           ^
          ^     ^             ^             ^       ^            ^
         ^       ^           ^              ^      ^             ^
        ^         ^         ^               ^     ^              ^
       ^           ^       ^                ^    ^               ^
      ^             ^     ^                 ^   ^                ^
     ^               ^   ^                  ^  ^                 ^
    ^                 ^ ^                   ^ ^                  ^

                                                      ^
                                                      ^
                                                      ^
    ^                 ^ ^                 ^ ^                  ^^
     ^               ^   ^               ^  ^                 ^ ^
      ^             ^     ^             ^   ^                ^  ^
       ^           ^       ^           ^    ^               ^   ^
        ^         ^         ^         ^     ^              ^    ^
         ^       ^           ^       ^      ^             ^     ^
          ^     ^             ^     ^       ^            ^      ^
           ^   ^               ^   ^        ^           ^       ^
            ^ ^                 ^ ^         ^          ^        ^
             ^                   ^          ^         ^         ^
            ^ ^                 ^           ^        ^          ^
           ^   ^               ^            ^       ^           ^
          ^     ^             ^             ^      ^            ^
         ^       ^           ^              ^     ^             ^
        ^         ^         ^               ^    ^              ^
       ^           ^       ^                ^   ^               ^
      ^             ^     ^                 ^  ^                ^
     ^               ^   ^                  ^ ^                 ^
    ^                 ^ ^                   ^^                  ^

                                                         '
                                                         '
                                                         '
                                                         '
    '                  ' '                  ' '                    ''
     '                '   '                '  '                   ' '
      '              '     '              '   '                  '  '
       '            '       '            '    '                 '   '
        '          '         '          '     '                '    '
         '        '           '        '      '               '     '
          '      '             '      '       '              '      '
           '    '               '    '        '             '       '
            '  '                 '  '         '            '        '
             ''                   ''          '           '         '
             ''                   '           '          '          '
            '  '                 '            '         '           '
           '    '               '             '        '            '
          '      '             '              '       '             '
         '        '           '               '      '              '
        '          '         '                '     '               '
       '            '       '                 '    '                '
      '              '     '                  '   '                 '
     '                '   '                   '  '                  '
    '                  ' '                    ' '                   '

                            @
    @       @ @       @ @       @@
     @     @   @     @  @      @ @
      @   @     @   @   @     @  @
       @ @       @ @    @    @   @
        @         @     @   @    @
       @ @       @      @  @     @
      @   @     @       @ @      @
     @     @   @        @@       @
    @       @ @         @        @

## Licence
WTFPL, grab your copy here: http://www.wtfpl.net/

## Disclaimer
It will be never used in linux kernel. So please dont email me again.
