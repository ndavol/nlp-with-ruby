# Awesome NLP with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="assets/Ruby_Logo.jpg" align="right" width="100px" height="100px" />](https://www.ruby-lang.org/en/)

> Useful resources for language processing in [Ruby](https://www.ruby-lang.org/en/)

This curated list comprizes [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about Computational Processing
of Human Languages with Ruby. This list comes from our day to day work
on Language Models and NLP Tools.

We plan to provide not only links but also a short _tutorial_ for every included tool.

Any help, suggestions and contributions are welcome! Please read the
[Contributors Guide](CONTRIBUTING.md) and refer the [Contribution](#contributing) section.

## Contents

* [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
  * [Segmentation](#segmentation)
  * [Lexical Processing](#lexical-processing)
  * [Phrasal Level Processing](#phrasal-level-processing)
  * [Syntactic Processing](#syntactic-processing)
    * [Dependency Parsing](#dependency-parsing)
    * [Constituency Parsing](#constituency-parsing)
  * [Semantic Analysis](#semantic-analysis)
  * [Pragmatical Analysis](#pragmatic-analysis)
* [High Level Tasks](#high-level-tasks)
  * [Word Sense Disambiguation](#word-sense-disambiguation)
  * [Machine Translation](#machine-translation)
  * [Question Answering](#question-answering)
  * [Sentiment Analysis](#sentiment-analysis)
* [Machine Learning Libraries](#machine-learning-libraries)
* [Other resources](#other-online-resources)
* [Books](#books)

## NLP Pipeline Subtasks

### Segmentation

Tools for Tokenization, Word and Sentence Boundary Detection and Disambiguation.

  * [tokenizer](https://github.com/arbox/tokenizer):
  A simple multilingual tokenizer. [![Tutorial][:fast_forward:]](tutorials/tokenizer.md)

  * [pragmatic_tokenizer](https://github.com/diasks2/pragmatic_tokenizer):
  A multilingual tokenizer to split a string into tokens.

  * [nlp-pure](https://github.com/parhamr/nlp-pure):
  Natural language processing algorithms implemented in pure Ruby with minimal dependencies.

  * [textoken](https://github.com/manorie/textoken):
  A simple and customizable text tokenization library.

  * [pragmatic_segmenter](https://github.com/diasks2/pragmatic_segmenter):
  A WBD tool with many cookies.

  * [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter):
  A pure Ruby implementation of the Punkt Segmenter.

  * [Tactful_Tokenizer](https://github.com/zencephalon/Tactful_Tokenizer):
  A RegExp based tokenizer for different languages.

  * [scapel](https://github.com/louismullie/scalpel):
  A Sentence Boundary Disambiguation tool.

### Lexical Processing

#### Stemming

Stemming is the term used in information retrieval to describe the process for
reducing wordforms to some base representation. Stemming should be distinguished
from [Lemmatization](#lemmatization) since `stems` are not necessarily have
a linguistic motivation.

* [ruby-stemmer](https://github.com/aurelian/ruby-stemmer):
  Ruby-Stemmer exposes the SnowBall API to Ruby. [![Tutorial][:fast_forward:]](tutorials/ruby-stemmer.md)

* [uea-stemmer](https://github.com/ealdent/uea-stemmer):
  A conservative stemmer for search and indexing.

#### Lemmatization
- [ ] Add some resources

### Phrasal Level Processing
- [ ] Add some resources

### Syntactic Processing
- [ ] Add some resources

#### Dependency Parsing
- [ ] Add some resources

#### Constituency Parsing
- [ ] Add some resources

### Semantic Analysis
- [ ] Add some resources

### Pragmatical Analysis
- [ ] Add some resources

## High Level Tasks

### Word Sense Disambiguation
- [ ] Add some resources

### Machine Translation
- [ ] Add some resources

### Question Answering
- [ ] Add some resources

### Sentiment Analysis
- [ ] Add some resources


## Machine Learning Libraries

Libraries in pure Ruby or written in other programming languages with appropriate bindings for Ruby.

* [rb-libsvm](https://github.com/febeling/rb-libsvm):
  Support Vector Machines with Ruby.

* [weka-jruby](https://github.com/paulgoetze/weka-jruby):
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
  [![Tutorial][tutorial-present]](tutorials/weka-jruby.md)

* [decisiontree](https://github.com/igrigorik/decisiontree):
  Decision Tree ID3 Algorithm in pure Ruby.

* [rtimbl](https://github.com/maspwr/rtimbl):
  Memory based learners from the Timbl framework.

## Language Aware String Manipulation

Libraries for language aware string manipulation, i.e. search, pattern matching,
case conversion, transcoding, regular expressions which need information about
the underlying language.

- [ ] Add some resources

## Other Online Resources

* [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing)
* [Ruby NLP](https://github.com/diasks2/ruby-nlp)
* [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing)
* [Scientific Ruby](http://sciruby.com/)

## Books

*  Miller, Rob. _Text Processing with Ruby: Extract Value from the Data That Surrounds You._
   Dallas: Pragmatic Bookshelf, 2015.
   <sup>[Amazon Link](http://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708/)</sup>


## Contributing

We are very glad to see you in this section and highly appreciate any help!

But we also take care about the quality of this list. If you want to contribute please

- read carefully the [Contribution Guidelines](CONTRIBUTING.md) and
- agree that your work will be published under the terms of the `CC0` license.

Some of the task for contributors are listed below.

## License

`Awesome NLP in Ruby` by Andrei Beliankou [![Creative Commons Zero 1.0]
(http://img.shields.io/badge/License-CC0-green.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the person who associated CC0 with
`Awesome NLP in Ruby` has waived all copyright and related or neighboring rights
to `Awesome NLP in Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <http://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->
[ruby]: https://img.shields.io/badge/L%3A-Ruby-red.svg
[jruby]: https://img.shields.io/badge/L%3A-JRuby-yellowgreen.svg
[java]: https://img.shields.io/badge/L%3A-Java-yellow.svg
[c]: https://img.shields.io/badge/L%3A-C-brightgreen.svg
[cpp]: https://img.shields.io/badge/L%3A-C%2B%2B-green.svg
[tutorial-present]: https://img.shields.io/badge/Tutorial-%E2%9C%85-green.svg
[tutorial-missing]: https://img.shields.io/badge/Tutorial-%E2%9C%98-lightgrey.svg
