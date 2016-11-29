# Awesome NLP with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="assets/Ruby_Logo.jpg" align="right" width="100px" height="100px" />](https://www.ruby-lang.org/en/)

> Useful resources for text processing in [Ruby](https://www.ruby-lang.org/en/)

This curated list comprises [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about computational processing
of human languages with Ruby. It comes from our day to day work on Language
Models and NLP Tools. Read [why](motivation.md) this list is awesome.

Any help, suggestions and contributions are welcome! Please read the
[Contributors Guide](CONTRIBUTING.md) and refer the [Contribution](#contributing) section.

## Contents

<!-- toc -->

- [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
  - [Multipurpose Engines](#multipurpose-engines)
  - [Segmentation](#segmentation)
  - [Lexical Processing](#lexical-processing)
    - [Stemming](#stemming)
    - [Lemmatization](#lemmatization)
    - [Counting Types and Tokens](#counting-types-and-tokens)
  - [Phrasal Level Processing](#phrasal-level-processing)
  - [Syntactic Processing](#syntactic-processing)
    - [Constituency Parsing](#constituency-parsing)
  - [Semantic Analysis](#semantic-analysis)
  - [Pragmatical Analysis](#pragmatical-analysis)
- [High Level Tasks](#high-level-tasks)
  - [Text Alignment](#text-alignment)
  - [Machine Translation](#machine-translation)
  - [Dialog Systems](#dialog-systems)
  - [Sentiment Analysis](#sentiment-analysis)
  - [Date and Time Parsing](#date-and-time-parsing)
  - [Named Entity Recognition](#named-entity-recognition)
  - [Text-to-Speech-to-Text](#text-to-speech-to-text)
- [Machine Learning Libraries](#machine-learning-libraries)
- [Language Aware String Manipulation](#language-aware-string-manipulation)
- [Other Online Resources](#other-online-resources)
- [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
- [Books](#books)
- [Community](#community)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

## NLP Pipeline Subtasks

### Multipurpose Engines

- [Open NLP](https://github.com/louismullie/open-nlp) -
  Ruby Bindings for the OpenNLP Toolkit.
- [Stanford Core NLP](https://github.com/louismullie/stanford-core-nlp) -
  Ruby Bindings for the Stanford CoreNLP tools.
- [Treat](https://github.com/louismullie/treat) -
  Natural Language Processing framework for Ruby.

### Segmentation

Tools for Tokenization, Word and Sentence Boundary Detection and Disambiguation.

- [tokenizer](https://github.com/arbox/tokenizer) -
  Simple multilingual tokenizer.
  <sup>[[tutorial](tutorials/tokenizer.md)]</sup>
- [pragmatic_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) -
  Multilingual tokenizer to split a string into tokens.
- [nlp-pure](https://github.com/parhamr/nlp-pure) -
  Natural language processing algorithms implemented in pure Ruby with minimal dependencies.
- [textoken](https://github.com/manorie/textoken) -
  Simple and customizable text tokenization library.
- [pragmatic_segmenter](https://github.com/diasks2/pragmatic_segmenter) -
  Word Boundary Disambiguation with many cookies.
- [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) -
  Pure Ruby implementation of the Punkt Segmenter.
- [Tactful_Tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) -
  RegExp based tokenizer for different languages.
- [scapel](https://github.com/louismullie/scalpel) -
  Sentence Boundary Disambiguation tool.

### Lexical Processing

#### Stemming

Stemming is the term used in information retrieval to describe the process for
reducing wordforms to some base representation. Stemming should be distinguished
from [Lemmatization](#lemmatization) since `stems` are not necessarily have
linguistic motivation.

- [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) -
  Ruby-Stemmer exposes the SnowBall API to Ruby.
  <sup>[[tutorial]](tutorials/ruby-stemmer.md)</sup>
- [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
  Conservative stemmer for search and indexing.

#### Lemmatization

Lemmatization is considered a process of finding a base form of a word. Lemmas
are often collected in dictionaries.

- [lemmatizer](https://github.com/yohasebe/lemmatizer) -
  WordNet based Lemmatizer for English texts.

#### Counting Types and Tokens

- [wc](https://github.com/thesp0nge/wc) -
  Facilities to count word occurrences in a text.
- [word_count](https://github.com/AtelierConvivialite/word_count) -
  Word counter for `String` and `Hash` objects.

### Phrasal Level Processing

- [N-Gram](https://github.com/reddavis/N-Gram) -
  N-Gram generator.
- [ngram](https://github.com/tkellen/ruby-ngram) -
  Break words and phrases into ngrams.
- [raingrams](https://github.com/postmodern/raingrams) -
  Flexible and general-purpose ngrams library written in pure Ruby.

### Syntactic Processing

#### Constituency Parsing

- [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  Ruby based wrapper for the Stanford Parser.

### Semantic Analysis

- [amatch](https://github.com/flori/amatch) -
  Set of five distance types between strings (including Levenshtein, Sellers, Jaro-Winkler, 'pair distance').
- [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) -
  Calculates edit distance using the Damerau-Levenshtein algorithm.
- [FuzzyTools](https://github.com/brianhempel/fuzzy_tools) -
  In-memory TF/IDF fuzzy document finding with a fancy default tokenizer.
- [Going the Distance](https://github.com/schneems/going_the_distance) -
  Contains scripts that do various distance calculations.
- [hotwater](https://github.com/colinsurprenant/hotwater) -
  Fast Ruby FFI string edit distance algorithms.
- [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) -
  Fast string edit distance computation, using the Damerau-Levenshtein algorithm.
- [TF-IDF](https://github.com/reddavis/TF-IDF) -
  Term Frequency / Inverse Document Frequency in pure Ruby.
- [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) -
  Calculate the similarity between texts using TF/IDF.

### Pragmatical Analysis
- [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
  Simple extensible sentiment analysis gem.

## High Level Tasks

### Text Alignment

- [alignment](https://github.com/bloomrain/alignment) -
  Alignment routines for bilingual texts (Gale-Church implementation).

### Machine Translation

- [Google API Client](https://github.com/google/google-api-ruby-client) -
  Google API Ruby Client.
- [microsoft_translator](https://github.com/ikayzo/microsoft_translator) -
  Ruby client for the microsoft translator API.
- [termit](https://github.com/pawurb/termit) -
  Google Translate with speech synthesis in your terminal.

### Dialog Systems

- [chatterbot](https://github.com/muffinista/chatterbot) -
  Straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate.
- [Lita](https://github.com/jimmycuadra/lita) -
  Lita is a chat bot written in Ruby with persistent storage provided by Redis.

### Sentiment Analysis
- [Stimmung](https://github.com/pachacamac/stimmung) -
  Semantic Polarity based on [SentiWS](http://wortschatz.informatik.uni-leipzig.de/download/sentiws.html).

### Date and Time Parsing

- [Chronic](https://github.com/mojombo/chronic) -
  Pure Ruby natural language date parser
- [Chronic Between](https://github.com/jrobertson/chronic_between) -
  Simple Ruby natural language parser for date and time ranges.
- [Chronic Duration](https://github.com/hpoydar/chronic_duration) -
  Pure Ruby parser for elapsed time.
- [Kronic](https://github.com/xaviershay/kronic) -
  Methods for parsing and formatting human readable dates.
- [Nickel](https://github.com/iainbeeston/nickel) -
  Extracts date, time, and message information from naturally worded text.
- [Tickle](https://github.com/yb66/tickle) -
  Parser for recurring and repeating events.

### Named Entity Recognition

- [ruby-ner](https://github.com/mblongii/ruby-ner) -
  Named Entity Recognition with Stanford NER and Ruby.
- [ruby-nlp](https://github.com/tiendung/ruby-nlp) -
  Ruby Binding for Stanford Pos-Tagger and Name Entity Recognizer.

### Text-to-Speech-to-Text

- [espeak-ruby](https://github.com/dejan/espeak-ruby) -
  Small Ruby API for utilizing 'espeak' and 'lame' to create text-to-speech mp3 files.
- [Isabella](https://github.com/chrisvfritz/isabella) -
  Voice-computing assistant built in Ruby.
- [tts](https://github.com/c2h2/tts) -
  Text-to-Speech conversion using the Google translate service.
- [att_speech](https://github.com/adhearsion/att_speech) -
  Ruby wrapper over the AT&T Speech API for speech to text.
- [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) -
  Pocketsphinx bindings.

## Machine Learning Libraries

Machine Learining Algorithms in pure Ruby or written in other programming
languages with appropriate bindings for Ruby.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  Support Vector Machines with Ruby.
- [weka-jruby](https://github.com/paulgoetze/weka-jruby) -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  Decision Tree ID3 Algorithm in pure Ruby.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  Memory based learners from the Timbl framework.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  General classifier module to allow Bayesian and other types of classifications.
- [Latent Dirichlet Allocation](https://github.com/ealdent/lda-ruby) -
  Pure Ruby LDA implementation to automatically cluster documents into topics.
- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis-backed Bayesian classifier.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
- [Naive-Bayes](https://github.com/reddavis/Naive-Bayes) -
  Simple Naive Bayes classifier.
- [nbayes](https://github.com/oasic/nbayes) -
  Full-featured, Ruby implementation of Naive Bayes.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  Generalized rack framework for text classifications.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  Naive Bayes text classification implementation as an OmniCat classifier strategy.

## Language Aware String Manipulation

Libraries for language aware string manipulation, i.e. search, pattern matching,
case conversion, transcoding, regular expressions which need information about
the underlying language.

- [FuzzyMatch](https://github.com/seamusabshere/fuzzy_match) -
  find a needle in a haystack based on string similarity and regular expression rules.
- [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) -
  Fuzzy string matching library for Ruby.
- [active_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
  RoR `ActiveSupport` gem has various string extensions that can handle case.
- [u](http://disu.se/software/u-1.0/) -
  U extends Ruby’s Unicode support.
- [unicode](https://github.com/blackwinter/unicode) -
  Unicode normalization library.
- [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) -
  Find a lot of kinds of common information in a string.
- [regexp-examples](https://github.com/tom-lord/regexp-examples) -
  Generate strings that match a given regular expression.
- [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) -
  Make difficult regular expressions easy.

## Other Online Resources

- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  Short list of NLP related projects.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  State-of-Art collection of Ruby libraries for NLP.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  General List of NLP related resources not mostly not for Ruby programmers.
- [Scientific Ruby](http://sciruby.com/) -
  Linear Algebra, Visualization and Scientific Computing for Ruby.

## Articles, Posts, Talks, and Presentations

- 2016
  - _Quickly Create a Telegram Bot in Ruby_ by Ardian Haxha
    <sup>[[tutorial](http://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
- 2015
  - _N-gram Analysis for Fun and Profit_ by [Jesus Castello](https://github.com/matugm)
    <sup>[[tutorial](http://www.blackbytes.info/2015/09/ngram-analysis-ruby/)]</sup>
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](http://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - _Using Ruby Machine Learning to Find Paris Hilton Quotes_ by [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  - _Exploring Natural Language Processing in Ruby_ by [Kevin Dias](https://github.com/diasks2)
    <sup>[[slides](http://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
- 2014
  - _Natural Language Parsing with Ruby_ by [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://blog.glaucocustodio.com/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  - _Demystifying Data Science: Analyzing Conference Talks with Rails and Ngrams_ by [Todd Schneider](https://github.com/toddwschneider)
    <sup>[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
  - _Natural Language Processing with Ruby_ by [Konstantin Tennhard](https://github.com/t6d)
    <sup>[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU)]</sup>
- 2013
  - _How to parse 'go' - Natural Language Processing in Ruby_
    by [Tom Cartwright](https://github.com/tomcartwrightuk)
    <sup>[[slides](http://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby)]</sup>
  - _Natural Language Processing in Ruby_ by [Brandon Black](https://github.com/brandonblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  - _Natural Language Processing with Ruby: n-grams_ by [Nathan Kleyn](https://github.com/nathankleyn)
  <sup>[[tutorial](http://www.sitepoint.com/natural-language-processing-ruby-n-grams/)]</sup>
  - _A Tour Through Random Ruby_ by Robert Qualls
    <sup>[[tutorial](http://www.sitepoint.com/tour-random-ruby/)]</sup>
- 2011
  - _Ruby one-liners_ by [Benoit Hamelin](https://twitter.com/benoithamelin)
  <sup>[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>

## Books

-  Miller, Rob. _Text Processing with Ruby: Extract Value from the Data That Surrounds You._
   Pragmatic Programmers, 2015.
   <sup>[[link](http://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708/)]</sup>
-  Watson, Mark. _Scripting Intelligence: Web 3.0 Information Gathering and Processing._
   APRESS, 2010.
   <sup>[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510/)]</sup>

## Community

- [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp&src=typd&lang=en)
- [Stack Overflow](http://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)

## Contributing

We are very glad to see you in this section and highly appreciate any help!

But we also take care about the quality of this list. If you want to contribute please

- read carefully the [Contribution Guidelines](CONTRIBUTING.md) and
- agree that your work will be published under the terms of the `CC0` license.

Some of the open tasks for contributors are listed in the [todo file](todo.md).
You may want to start there.

## License

`Awesome NLP in Ruby` by Andrei Beliankou [![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

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
