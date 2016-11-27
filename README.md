# Awesome NLP with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="assets/Ruby_Logo.jpg" align="right" width="100px" height="100px" />](https://www.ruby-lang.org/en/)

> Useful resources for text processing in [Ruby](https://www.ruby-lang.org/en/)

This curated list comprises [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about computational processing
of human languages with Ruby. It comes from our day to day work on Language
Models and NLP Tools.

Any help, suggestions and contributions are welcome! Please read the
[Contributors Guide](CONTRIBUTING.md) and refer the [Contribution](#contributing) section.

## Contents

<!-- toc -->

- [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
  * [Multipurpose Engines](#multipurpose-engines)
  * [Segmentation](#segmentation)
  * [Lexical Processing](#lexical-processing)
    + [Stemming](#stemming)
    + [Lemmatization](#lemmatization)
    + [Counting Types and Tokens](#counting-types-and-tokens)
  * [Phrasal Level Processing](#phrasal-level-processing)
  * [Syntactic Processing](#syntactic-processing)
    + [Constituency Parsing](#constituency-parsing)
  * [Semantic Analysis](#semantic-analysis)
  * [Pragmatical Analysis](#pragmatical-analysis)
- [High Level Tasks](#high-level-tasks)
  * [Text Alignment](#text-alignment)
  * [Machine Translation](#machine-translation)
  * [Dialog Systems](#dialog-systems)
  * [Sentiment Analysis](#sentiment-analysis)
  * [Date and Time Parsing](#date-and-time-parsing)
  * [Named Entity Recognition](#named-entity-recognition)
  * [Text-to-Speech-to-Text](#text-to-speech-to-text)
- [Machine Learning Libraries](#machine-learning-libraries)
- [Language Aware String Manipulation](#language-aware-string-manipulation)
- [Other Online Resources](#other-online-resources)
- [Talks and Presentations](#talks-and-presentations)
- [Books](#books)
- [Community](#community)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

* [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
  + [Segmentation](#segmentation)
  + [Lexical Processing](#lexical-processing)
    - [Stemming](#stemming)
    - [Lemmatization](#lemmatization)
  + [Phrasal Level Processing](#phrasal-level-processing)
  + [Syntactic Processing](#syntactic-processing)
    - [Dependency Parsing](#dependency-parsing)
    - [Constituency Parsing](#constituency-parsing)
  + [Semantic Analysis](#semantic-analysis)
  + [Pragmatical Analysis](#pragmatical-analysis)
* [High Level Tasks](#high-level-tasks)
  + [Word Sense Disambiguation](#word-sense-disambiguation)
  + [Machine Translation](#machine-translation)
  + [Question Answering](#question-answering)
  + [Sentiment Analysis](#sentiment-analysis)
  + [Date and Time Parsing](#date-and-time-parsing)
* [Machine Learning Libraries](#machine-learning-libraries)
* [Language Aware String Manipulation](#language-aware-string-manipulation)
* [Other Online Resources](#other-online-resources)
* [Talks and Presentations](#talks-and-presentations)
* [Books](#books)
* [Community](#community)
* [Contributing](#contributing)
* [License](#license)

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

* [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
  Conservative stemmer for search and indexing.

#### Lemmatization

Lemmatization is considered a process of finding a base form of a word. Lemmas
are often collected in dictionaries.

- [lemmatizer](https://github.com/yohasebe/lemmatizer) -
  WordNet based Lemmatizer for English texts.

#### Counting Types and Tokens

* [wc](https://github.com/thesp0nge/wc) - a rubygem to count word occurrences in a given text
* [word_count](https://github.com/AtelierConvivialite/word_count) - a word counter for String and Hash in Ruby
* [Word Count Analyzer](https://github.com/diasks2/word_count_analyzer) - analyzes a string for potential areas of the text that might cause word count discrepancies depending on the tool used
* [WordsCounted](https://github.com/abitdodgy/words_counted) - a highly customisable Ruby text analyser

### Phrasal Level Processing

* [N-Gram](https://github.com/reddavis/N-Gram) - N-Gram generator in Ruby
* [ngram](https://github.com/tkellen/ruby-ngram) - break words and phrases into ngrams
* [raingrams](https://github.com/postmodern/raingrams) - a flexible and general-purpose ngrams library written in Ruby

### Syntactic Processing

#### Constituency Parsing

- [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  Ruby based wrapper for the Stanford Parser.

### Semantic Analysis

* [amatch](https://github.com/flori/amatch) - collection of five type of distances between strings (including Levenshtein, Sellers, Jaro-Winkler, 'pair distance'. Last one seems to work well to find similarity in long phrases)
* [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) - calculates edit distance using the Damerau-Levenshtein algorithm
* [FuzzyMatch](https://github.com/seamusabshere/fuzzy_match) - find a needle in a haystack based on string similarity and regular expression rules
* [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) - fuzzy string matching library for ruby
* [FuzzyTools](https://github.com/brianhempel/fuzzy_tools) - In-memory TF-IDF fuzzy document finding with a fancy default tokenizer tuned on diverse record linkage datasets for easy out-of-the-box use
* [Going the Distance](https://github.com/schneems/going_the_distance) - contains scripts that do various distance calculations
* [hotwater](https://github.com/colinsurprenant/hotwater) - Fast Ruby FFI string edit distance algorithms
* [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) - fast string edit distance computation, using the Damerau-Levenshtein algorithm
* [TF-IDF](https://github.com/reddavis/TF-IDF) - Term Frequency - Inverse Document Frequency in Ruby
* [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) - calculate the similarity between texts using tf*idf

### Pragmatical Analysis
- [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
  Simple extensible sentiment analysis gem.

## High Level Tasks

### Text Alignment

- [alignment](https://github.com/bloomrain/alignment) -
  Alignment functions for corpus linguistics (Gale-Church implementation)

### Machine Translation

* [Google API Client](https://github.com/google/google-api-ruby-client) - Google API Ruby Client
* [microsoft_translator](https://github.com/ikayzo/microsoft_translator) - Ruby client for the microsoft translator API
* [termit](https://github.com/pawurb/termit) - Google Translate with speech synthesis in your terminal as ruby gem

### Dialog Systems

- [chatterbot](https://github.com/muffinista/chatterbot) -
  Straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate.
- [Lita](https://github.com/jimmycuadra/lita) -
  Lita is a chat bot written in Ruby with persistent storage provided by Redis.

### Sentiment Analysis
- [Stimmung](https://github.com/pachacamac/stimmung) -
  Semantic Polarity based on (SentiWS](http://wortschatz.informatik.uni-leipzig.de/download/sentiws.html)

### Date and Time Parsing

- [Chronic](https://github.com/mojombo/chronic) -
  pure Ruby natural language date parser
- [Chronic Between](https://github.com/jrobertson/chronic_between) -
  simple Ruby natural language parser for date and time ranges
- [Chronic Duration](https://github.com/hpoydar/chronic_duration) -
  simple Ruby natural language parser for elapsed time
- [Kronic](https://github.com/xaviershay/kronic) -
  dirt simple library for parsing and formatting human readable dates
- [Nickel](https://github.com/iainbeeston/nickel) -
  extracts date, time, and message information from naturally worded text
- [Tickle](https://github.com/yb66/tickle) -
  natural language parser for recurring events


### Named Entity Recognition

- [Confidential Info Redactor](https://github.com/diasks2/confidential_info_redactor) -
  a Ruby gem to semi-automatically redact confidential information from a text
- [ruby-ner](https://github.com/mblongii/ruby-ner) - named entity recognition with Stanford NER and Ruby
- [ruby-nlp](https://github.com/tiendung/ruby-nlp) - Ruby Binding for Stanford Pos-Tagger and Name Entity Recognizer


### Text-to-Speech-to-Text

* [espeak-ruby](https://github.com/dejan/espeak-ruby) - small Ruby API for utilizing 'espeak' and 'lame' to create text-to-speech mp3 files
* [Isabella](https://github.com/chrisvfritz/isabella) - a voice-computing assistant built in Ruby
* [tts](https://github.com/c2h2/tts) - a ruby gem for converting text-to-speech using the Google translate service
* [att_speech](https://github.com/adhearsion/att_speech) - A Ruby library for consuming the AT&T Speech API for speech to text
* [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) - Ruby speech recognition with Pocketsphinx
* [Speech2Text](https://github.com/taf2/speech2text) - using Google Speech to Text API Provide a Simple Interface to Convert Audio Files

## Machine Learning Libraries

Libraries in pure Ruby or written in other programming languages with appropriate bindings for Ruby.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) - Support Vector Machines with Ruby.

- [weka-jruby](https://github.com/paulgoetze/weka-jruby) -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
  <sup>[[tutorial](tutorials/weka-jruby.md)]</sup>

- [decisiontree](https://github.com/igrigorik/decisiontree) -
  Decision Tree ID3 Algorithm in pure Ruby.

- [rtimbl](https://github.com/maspwr/rtimbl) -
  Memory based learners from the Timbl framework.

* [Classifier](https://github.com/cardmagic/classifier) - a general module to allow Bayesian and other types of classifications
* [classifier-reborn](https://github.com/jekyll/classifier-reborn) - (a fork of cardmagic/classifier) a general classifier module to allow Bayesian and other types of classifications
* [Latent Dirichlet Allocation](https://github.com/ealdent/lda-ruby) - used to automatically cluster documents into topics
* [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) - Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification and other large linear classifications)
* [linnaeus](https://github.com/djcp/linnaeus) - a redis-backed Bayesian classifier
* [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) - a JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework
* [Naive-Bayes](https://github.com/reddavis/Naive-Bayes) - simple Naive Bayes classifier
* [nbayes](https://github.com/oasic/nbayes) - a full-featured, Ruby implementation of Naive Bayes
* [omnicat](https://github.com/mustafaturan/omnicat) - a generalized rack framework for text classifications
* [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) - Naive Bayes text classification implementation as an OmniCat classifier strategy
* [stuff-classifier](https://github.com/alexandru/stuff-classifier) - a library for classifying text into multiple categories


## Language Aware String Manipulation

Libraries for language aware string manipulation, i.e. search, pattern matching,
case conversion, transcoding, regular expressions which need information about
the underlying language.

- [active_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
  RoR `ActiveSupport` gem has various string extensions that can handle case (e.g. `.mb_chars.upcase.to_s` or #transliterate)
- [twitter-cldr-rb](https://github.com/twitter/twitter-cldr-rb/blob/master/lib/twitter_cldr/shared/casefolder.rb) - casefolding
- [u](http://disu.se/software/u-1.0/) - U extends Ruby’s Unicode support
- [unicode](https://github.com/blackwinter/unicode) - Unicode normalization library
- [unicode_utils](https://github.com/lang/unicode_utils) - Unicode algorithms for Ruby 1.9
- [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) - find a lot of kinds of common information in a string
- [regexp-examples](https://github.com/tom-lord/regexp-examples) - generate strings that match a given regular expression
- [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) - make difficult regular expressions easy

## Other Online Resources

- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing)
- [Ruby NLP](https://github.com/diasks2/ruby-nlp)
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing)
- [Scientific Ruby](http://sciruby.com/)

## Talks and Presentations

- 2016
  - *Quickly Create a Telegram Bot in Ruby* by Ardian Haxha
    [[tutorial](http://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]

- 2015
  - *N-gram Analysis for Fun and Profit* by [Jesus Castello](https://github.com/matugm)
    [[tutorial](http://www.blackbytes.info/2015/09/ngram-analysis-ruby/)]

  - *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://github.com/rugginoso)
    [[tutorial](http://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]

  - *Using Ruby Machine Learning to Find Paris Hilton Quotes* by [Rick Carlino](https://github.com/RickCarlino)
    [[tutorial](http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]

  - *Exploring Natural Language Processing in Ruby* by [Kevin Dias](https://github.com/diasks2)
    [[slides](http://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]

- 2014
  - *Natural Language Parsing with Ruby* by [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://blog.glaucocustodio.com/2014/11/10/natural-language-parsing-with-ruby/)]</sup>

  - *Demystifying Data Science (Analyzing Conference Talks with Rails and Ngrams)* by [Todd Schneider](https://github.com/toddwschneider)
    [[video RailsConf 2014](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [Repo from the Video](https://github.com/Genius/abstractogram)]

  - *Natural Language Processing with Ruby* by [Konstantin Tennhard](https://github.com/t6d)
    [[video ArrrrCamp 2014](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video Ruby Conf India](https://www.youtube.com/watch?v=oFmy_QBQ5DU)]

- 2013
  - _How to parse 'go' - Natural Language Processing in Ruby_  by [Tom Cartwright](https://github.com/tomcartwrightuk)
    [[slides](http://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby)]

  - *Natural Language Processing in Ruby* by [Brandon Black](https://github.com/brandonblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>

  - _Natural Language Processing with Ruby: n-grams_ by [Nathan Kleyn](https://github.com/nathankleyn)
    [[tutorial](http://www.sitepoint.com/natural-language-processing-ruby-n-grams/)]

  - _A Tour Through Random Ruby_ by Robert Qualls
    <sup>[[tutorial](http://www.sitepoint.com/tour-random-ruby/)]</sup>

## Books

-  Miller, Rob. _Text Processing with Ruby: Extract Value from the Data That Surrounds You._
   Dallas: Pragmatic Bookshelf, 2015.
   <sup>[[link](http://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708/)]</sup>
-  Watson, Mark. _Scripting Intelligence: Web 3.0 Information Gathering and Processing._
   APRESS, 2010.
   <sup>[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510/)]</sup>

## Community

- [Twitter](https://twitter.com/search?q=%23nlproc)
- [StackOverflow](http://stackoverflow.com/questions/tagged/nlp)

## Contributing

We are very glad to see you in this section and highly appreciate any help!

But we also take care about the quality of this list. If you want to contribute please

- read carefully the [Contribution Guidelines](CONTRIBUTING.md) and
- agree that your work will be published under the terms of the `CC0` license.

Some of the open tasks for contributors are listed in the [todo file](todo.md).
You may want to start there.

## License

`Awesome NLP in Ruby` by Andrei Beliankou [![Creative Commons Zero 1.0]
(http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by-nc-nd.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

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
