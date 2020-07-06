# plot marble diagram

plot marble diagram for reactiveX by rxmarbles  [https://bitbucket.org/achary/rx-marbles/src/master/]

# install rxmarbles

pip install rxmarbles

# svg

`marblesgen foo.txt`


# syntaxs

svg name:
    marble [name]
    {

    }
not the txt file name


timeline:
- starting time point: .
- start: + 
- step: -
- end:
    - simple: >
    - complete: |
    - error: #

item:
    - single character: (a-z, A-Z, 0-9)
    - multiple character: ()

2-nd order timelines: 
source name: {}

Grouped items:
{1,2}

Operators:
operator myTransformation:  +-A-B-C-|

commet: //


# plot demos in [rxmarbles/syntax.md]
cd ./text

marblesgen foo.txt
marblesgen three.txt
marblesgen endings.txt
marblesgen no_confusion.txt
marblesgen paddings.txt
marblesgen nested.txt
marblesgen grouped.txt
marblesgen exampleOperator.txt