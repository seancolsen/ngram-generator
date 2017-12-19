# N-gram Generator

This is a quick and dirty script which generates random sets of [n-grams](https://en.wikipedia.org/wiki/N-gram) to serve as lessons for touch typing practice. 

## Examples

```
$ ngrams
be be an an at at le le eetin eetin eetin eetin eetin publi publi publi publi
publi night night night night night the the the may may may lit lit lit cci cci
cci ina ina ina lf lf rma rma rma north north north north north arget arget
arget arget arget was was was th th pa pa
```

```
$ ngrams
iona iona iona iona ompa ompa ompa ompa sh sh ro ro ete ete ete much much much
much vid vid vid avo avo avo the the the th th ntia ntia ntia ntia ill ill ill
bout bout bout bout other other other other other goti goti goti goti local
local local local local yth yth yth would would would would would
```

```
$ ngrams
aus aus aus side side side side or or this this this this tra tra tra in in wi
wi ect ect ect ommon ommon ommon ommon ommon rst rst rst lac lac lac th th ap ap
eps eps eps evi evi evi ti ti and and and nonp nonp nonp nonp we we left left
left left ement ement ement ement ement
```

## Features

* Generates n-grams to match their frequency in English (by using data from the [American National Corpus](http://www.anc.org/data/anc-second-release/frequency-data/), partially truncated).
* Repeats each ngram multiple times. Longer ngrams are repeated more times.
* Wraps words at 80 character

## Limitations

* Doesn't accept any inputs. (However, you can adjust some of the behavior by altering the constants at the start of the script.)
* No capitals.
* No punctuation.

## Requirements

* PHP 5.4+