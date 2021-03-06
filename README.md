# wordcount

Counting words in different programming languages.

See the article on this project:
http://juditacs.github.io/2015/11/26/wordcount.html

or the follow-up article:
http://juditacs.github.io/2016/03/19/wordcount2.html

# Leaderboard

## Full Hungarian Wikipedia

Updated: April 16, 2016

Only the ones that finish are listed. The rest run out of memory.

| Rank | Experiment | CPU seconds | User time | Maximum memory | Contributor |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | rust/wordcount/wordcount | 154.86 | 148.16 | 6867252 | Joshua Holmer | 
| 2 | java -Xmx6G -classpath java:java/trove-3.0.3.jar WordCountOptimized | 217.75 | 262.39 | 3929384 | Sam Van Oort | 
| 3 | cpp/wordcount_clang | 225.96 | 214.96 | 4373408 |  | 
| 4 | cpp/wordcount | 230.23 | 217.0 | 4373432 | Dmitry Andreev, Matias Fontanini, Judit Acs | 
| 5 | d/wordcount | 231.02 | 219.36 | 6294800 | Pavel Chebotarev | 
| 6 | c/wordcount | 296.55 | 284.99 | 2424084 | gaebor | 
| 7 | python/wordcount_py2.py | 302.02 | 289.65 | 3893812 | Gabor Szabo | 
| 8 | go/bin/wordcount | 315.19 | 305.57 | 6084804 | David Siklosi | 
| 9 | php7.0 php/wordcount.php | 324.69 | 233.06 | 4108972 | Andrey Bukatov, Braun Patrik | 
| 10 | hhvm php/wordcount.php | 408.28 | 286.06 | 4964372 | Andrey Bukatov, Braun Patrik | 
| 11 | mono csharp/WordCount.exe | 466.53 | 447.97 | 4464920 | Joe Amenta, Tim Posey, Peter Szel | 
| 12 | python/wordcount_py2_baseline.py | 511.12 | 490.27 | 8802472 | Judit Acs | 
| 13 | php5.6 php/wordcount.php | 718.46 | 602.91 | 12564676 | Andrey Bukatov, Braun Patrik | 
| 14 | perl/wordcount.pl | 778.48 | 758.74 | 7100124 | Larion Garaczi, Judit Acs | 
| 15 | java -Xmx6G -classpath java WordCountBaseline | 791.52 | 1077.33 | 6150272 | Sam Van Oort, Rick Hendricksen, Dávid Márk Nemeskey | 
| 16 | python/wordcount_py3.py | 877.93 | 854.83 | 7672096 | Judit Acs | 
| 17 | lua lua/wordcount.lua | 1134.88 | 1029.69 | 7023604 | daurnimator | 
| 18 | julia julia/wordcount.jl | 1554.77 | 1519.4 | 7393432 | Attila Zseder, getzdan | 
| 19 | elixir/wordcount | 2214.77 | 2065.93 | 12584512 | Norbert Melzer | 
| 20 | bash/wordcount.sh | 2432.64 | 2538.23 | 13772 | Judit Acs | 
| 21 | cpp/wordcount_baseline | 3005.61 | 2909.42 | 5965548 | Judit Acs | 

## 5 million lines from the Hungarian Wikipedia

Updated: April 16, 2016

| Rank | Experiment | CPU seconds | User time | Maximum memory | Contributor |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | rust/wordcount/wordcount | 21.23 | 20.28 | 990008 | Joshua Holmer | 
| 2 | java -Xmx6G -classpath java:java/trove-3.0.3.jar WordCountOptimized | 29.76 | 34.41 | 962244 | Sam Van Oort | 
| 3 | d/wordcount | 29.79 | 28.97 | 752676 | Pavel Chebotarev | 
| 4 | cpp/wordcount | 33.58 | 32.51 | 758728 | Dmitry Andreev, Matias Fontanini, Judit Acs | 
| 5 | cpp/wordcount_clang | 33.84 | 32.95 | 758724 |  | 
| 6 | go/bin/wordcount | 38.84 | 37.86 | 859284 | David Siklosi | 
| 7 | python/wordcount_py2.py | 38.89 | 37.98 | 595500 | Gabor Szabo | 
| 8 | c/wordcount | 39.64 | 38.49 | 427180 | gaebor | 
| 9 | php7.0 php/wordcount.php | 41.11 | 27.13 | 709756 | Andrey Bukatov, Braun Patrik | 
| 10 | mono csharp/WordCount.exe | 48.18 | 46.37 | 836040 | Joe Amenta, Tim Posey, Peter Szel | 
| 11 | hhvm php/wordcount.php | 51.19 | 31.72 | 882584 | Andrey Bukatov, Braun Patrik | 
| 12 | python/wordcount_py2_baseline.py | 64.56 | 63.02 | 1438388 | Judit Acs | 
| 13 | php5.6 php/wordcount.php | 82.56 | 66.12 | 2113976 | Andrey Bukatov, Braun Patrik | 
| 14 | java -Xmx6G -classpath java WordCountBaseline | 89.12 | 111.27 | 1602580 | Sam Van Oort, Rick Hendricksen, Dávid Márk Nemeskey | 
| 15 | python/wordcount_py3.py | 98.33 | 96.62 | 1246564 | Judit Acs | 
| 16 | perl/wordcount.pl | 113.04 | 110.78 | 1242056 | Larion Garaczi, Judit Acs | 
| 17 | lua lua/wordcount.lua | 132.04 | 116.02 | 1210248 | daurnimator | 
| 18 | ruby2.3 ruby/wordcount.rb | 137.09 | 131.31 | 3847648 | Joshua Holmer | 
| 19 | java -classpath java WordCount | 143.01 | 128.67 | 1828536 |  | 
| 20 | julia julia/wordcount.jl | 152.88 | 146.15 | 2490572 | Attila Zseder, getzdan | 
| 21 | scala -J-Xmx2g -classpath scala Wordcount | 174.09 | 221.95 | 1457272 | Hans van den Bogert | 
| 22 | elixir/wordcount | 184.63 | 181.5 | 2590384 | Norbert Melzer | 
| 23 | bash/wordcount.sh | 276.14 | 290.33 | 13608 | Judit Acs | 
| 24 | haskell/WordCount | 295.73 | 286.33 | 4216656 | Larion Garaczi | 
| 25 | cpp/wordcount_baseline | 354.01 | 338.81 | 983292 | Judit Acs | 
| 26 | java -cp clojure.jar clojure.main clojure/wordcount.clj | 357.75 | 379.64 | 2158764 | lverweijen | 
| 27 | elixir elixir/wordcount.ex | 417.88 | 407.45 | 2545708 |  | 
| 28 | nodejs javascript/wordcount.js | 578.55 | 577.19 | 972904 | Laci Kundra | 
| 29 | nodejs typescript/wordcount.js | 628.72 | 604.63 | 920764 | Braun Patrik | 

# The task

The task is to split a text and count each word's frequency, then print the list sorted by frequency in decreasing order.
Ties are printed in alphabetical order.

## Rules

* the input is read from STDIN
* the input is always encoded in UTF-8
* output is printed to STDOUT
* break only on space, tab and newline (do not break on non-breaking space)
* do not write anything to STDERR
* the output is tab-separated
* sort by frequency AND secondary sort in alphabetical order
* try to write simple code with few dependencies
  * standard library
* single-thread is preferred but you can add multi-threaded or multicore versions too


The output should contain lines like this:

    freqword <tab> freq

## Example

    $ echo "apple pear apple art" | python2 python/wordcount.py
    apple   2
    art     1
    pear    1

## Test corpus: Hungarian Wikisource and Wikipedia

`scripts/create_input.sh` downloads and unpacks the latest Hungarian Wikisource XML dump.
Why Wikisource? It's not too small not too large and more importantly, it's valid utf8.
Why Hungarian? There are many non-ascii characters and the number of different word types is high.

`scripts/create_large_input.sh` downloads and unpacks the latest Hungarian Wikipedia.
This is the largest input used for comparison, see the first leaderboard.

### Usage

To test on a small sample:

    time cat data/huwikisource-latest-pages-meta-current.xml | head -10000 | python3 python/wordcount_py3.py > python_out

## Installation with Docker

I strongly recommend building the Docker image instead of installing every package manually, but it's possible to install the dependencies manually.
See the installation commands in `Dockerfile`.

## Docker image

You can run the experiment in a Docker container. 

Pull from DockerHub & tag it:

    docker pull svanoort/allthelanguages:latest && docker tag svanoort/allthelanguages:latest allthelanguages

If you wish to build locally (this while take quite a while):

    `docker build -t allthelanguages --rm .`

In either case, this requires quite a bit of storage, currently about 2.4 GB.

Run the image, mounting the local directory into the working directory of the docker file as a volume:

    `docker run -h DOCKER -it --rm -v $(pwd):/allthelanguages allthelanguages as_user.sh $(id -un) $(id -u) $(id -gn) $(id -g)`

Changes you made in the folder will show up in the docker container, and any output (builds, results) will write to the folder as well. All permissions are maintained.

**Note that if you're building node.js/typescript**, it needs root (non-sudo) access so you'll need to do it this way, which creates files with root as the owner (you'll need to chown them):

    `docker run -h DOCKER -it --rm -v $(pwd):/allthelanguages allthelanguages`

## Downloading the dataset

    bash scripts/create_input.sh

or the full dataset:

    bash scripts/create_large_input.sh

## Compile/build/whatever the wordcount scripts

    bash scripts/build.sh

## Run tests on one language

`scripts/test.sh` runs all tests for one language, well actually for a single command.

    bash scripts/test.sh "python2 python/wordcount_py2.py"

Or

    bash scripts/test.sh python/wordcount_py2.py

if the file is executable and has a valid shebang line.

The script either prints OK or the list of failed tests and a final FAIL.

## Run tests on all languages

All commands are listed in the file `run_commands.txt` and the script `scripts/test_all.sh` runs test.sh with each command:

    bash scripts/test_all.sh

## Run the actual experiment on a larger dataset

If all tests are passed, the scripts work reasonably well.
This does not mean that all output will be the same, see the full test later.
For now, we consider them good enough for testing.

This command will run each test twice and append the results to results.txt.
It's possible to add a comment at the end of each line.

    bash scripts/compare.sh data/huwikisource-latest-pages-meta-current.xml 2 "full huwikisource"

Or test it on a part of huwikisource:

    bash scripts/compare.sh <( head -10000 data/huwikisource-latest-pages-meta-current.xml) 1

Results.txt in a tab separated file that can be formatted to a Markdown table with this command:

    cat results.txt | python2 scripts/evaluate_results.py

This scripts prints the fastest run for each command in a markup table like this:

| Rank | Experiment | CPU seconds | User time | Maximum memory | Contributor |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | rust/wordcount/wordcount | 20.57 | 19.79 | 990008 | Joshua Holmer | 
| 2 | cpp/wc_vector | 33.3 | 31.93 | 775952 | Matias Fontanini, Judit Acs | 
| 3 | python/wordcount_py2gabor.py | 40.13 | 38.71 | 594800 | Gabor Szabo | 

## Adding a new program

Adding a new programming language or a new version for an existing programming language consists of the following steps:

1. Add dependencies to the Dockerfile. Basically add the package to the existing apt-get package list.
2. If it needs compiling or any other setup method, add it to `scripts/build.sh`
3. Add the actual invoke command to `run_commands.txt`
4. If your executable differs from the source file, add the executable - source code mapping to `binary_mapping.txt`. This is used by `scripts/evaluate_results.py` for finding out the contributors of each program. The file is <b>tab-separated</b>.

### Adding your program to this experiment

1. Make sure all dependencies are installed via standard packages and your code compiles.
1. Your code passes all the tests.
1. Make sure it runs for less than two minutes for 100,000 lines of text. If it is slower, it doesn't make much sense to add it.

