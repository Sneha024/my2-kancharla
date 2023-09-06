# Sneha Kancharla
Hi this is Sneha.I have recently undergraduated in july 2023.To start my new carrerr i think that i want to be more proffessional in  software feild, that make me to step into masters. Currently i am persuing masters in NWMSU. I am from Hyderabad.In my schooling i have received 1st price in srinivasa ramanjuna maths olympiad.In my under graduation i have volunteered in college events. I want to explore new places and I wish to make more friends.

![myimage](images/my_image.jpeg)

****
# sports
Sports help children develop physical skills, get exercise, make friends, have fun, learn teamwork, learn to play fair, and improve self-esteem. people enjoy watching sports because it provides a sense of entertainment, competition.

|Sport Name|reason|Hours|
|----------|------|-----|
|Tennicoit| promotes hand-eye coordination,fitness skills.|1|
|Hockey|It takes cooperation,teamwork |2|
|Golf|reduces stress,makes friends|1|
|Chess|develops problem solving skills,builds confidence|2|

****
****

# Quotes

>"It's never too late to be what you might've been" - George Eliot

>"Trust yourself that you can do it and get it" - Baz Luhrmann

>"If you can dream it, you can do it" - Walt Disney

# code fencing:

Link to stack overflow:
https://stackoverflow.com/questions/1129216/sort-array-of-objects-by-string-property-value

Sass:

```
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}



