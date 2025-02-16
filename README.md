# Initial research
## Executive functions
- planning - ability to follow individual steps to achive certail goal 
- mental flexibility - ability to adapt to ever changing enviroment
- inhibitory control - ability to control impulsive behavior
- working memory - ability to hold (short or longterm?) and manipulate information 
- emotional control - ability to regulate ones own emotions
- attention control - ability to hold focus on certain task while filtering unimportant information

## Initial research on existing testing methods
There is a huge amount of methods for testing different executive functions, each with its own benefits and dissadvantages. 
Methods itself are relatively easy to come by, main issue lies within their standardization, execution or evaluation. 
Some tests require presence of examiner or require proprietary testing materials. Another concenrn is evaluation of gathered test data. While paid tests ussualy come with standardized data set used for comparison, freely accesible methods often lack such data. 

---

## List of found methods
### Wisconsin card sorting test
Subject is given no rules and is tasked with matching presented card into 4 other cards in from of him. After matching said card subject is given feedback. Usual categories for matching are: color, shape, distribution of shapes on card. This category changes multiple times during the test.

### Iowa gambling task
Subject is presented with 4 packs of card. Each card yield certain amount of currency and has specific chance of penalty. Subject is tasked with making highest profit possible. Cards with higher yield have higher penalty, thus they are not benefitial in the long rune. Subject needs to deduce rules and overcome urge of getting large sums of money and prefer positive yield in the long term.

### mini-SEA (mini-Social cognition and Emotional Assessment)
- no detailed specification of testing method found
- requires examiner
- high sensitivity and specificity for diagnosis of frontotemporal dementia
- accurate discrimination of ftd patients from patients with Alzhaimers disease

### Test of Attentional Performance (TAP) tests
- proprietary? (https://www.psytest.net/en/test-batteries/tap/objective)
- no detailed info on testing method

### Stroop test
Subject is presented with congruent and incongruent stimuli. Incongruent stimuli refers to mismatch between color of the text and its meaning. Subjects typicaly take longer to respond to incongruent stimuli.

### Complex figure test
- difficult evaluation

Subject is presented with complex line drawing. Then is tasked to reproduce it by hand with image still visible. Immedietly after is tasked to reproduce image from memory. Same reprofuction is repeated after longer delay (~30min).

### Tower of london test
Subject is presented with two boards. One represents desired configuration and the other is in different configuration. Subject is tasked to reconfigure seconds board into first one in fewest steps possible.

### Trail making test (TMT)
Subject is presnted with board of numbers / letters. Subject is tasked with connection them in order with a line.

### Paced auditory serial addition (PASAT)
- requires audio output device

Subject is sequentialy presented a series of numbers. Subject is tasked with sum of two most recent numbers. 

### Continuous Atention Test (aka T.O.V.A)
- tests reaction time
- long (~20min)

Subject is presented binary set of images. Subject is tasked with pressing a button when certain image appears, otherwise do nothing.

---
# App proposal

## Selected testing methods
Selection of following test consider digital implementation of testing method, as well as their evaluation.
Each method could be easily self administered with app and evaluated immidietly after finishing the test. 
Selected test have broad coverage of tested areas, with exception of emotional and social executive functions.

### Evaluation
Problem with most selected methods is the lact of standardized data that could be used for evaluation. 
This problem could be circumvented by doing custom research that would yield standardized dataset for specific implementation of each test.
Another options is to leave the evaluation to educated individual, which would result in the inability to self administer said test battery.
NOTE: Most standardized studies ussualy use N~= 100. (higher = better)

### Coverage

|                   | TMT   | Stroop test   | PASAT | Tower of london   | Wisconsin card sorting    |
| ---               | ---   | ---           | ---   | ---               | ---                       |
|planning           |       |               |       |x                  |                           | 
|mental flexibility |x      |               |       |                   |x                          |
|inhibitory control |       |x              |       |                   |                           |
|working memory     |       |               |x      |x                  |                           |
|emotional control  |       |               |       |                   |                           |
|attention control  |       |x              |x      |                   |                           |

### Data for individual testing methods
#### Trail making test (TMT)
data - https://ftp.gwdg.de/pub/misc/MPI-Leipzig_Mind-Brain-Body-LEMON/Behavioural_Data_MPILMBB_LEMON/Cognitive_Test_Battery_LEMON/TMT/

#### Stroop test
test - https://ryanwingate.com/projects/hypothesis-testing-2/stroop/

#### Paced auditory serial addition (PASAT)
manual - http://www.pasat.us/PDF/PASAT_Manual.pdf

#### Tower of london test
- no data 

#### Wisconsin card sorting test
- no data

---

# Resources
https://pebl.sourceforge.net/index.html#about 

https://www.nature.com/articles/sdata2018308