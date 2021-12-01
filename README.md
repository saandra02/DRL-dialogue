## README
**A Simple Deep Reinforcement Learning Dialogue System** done as an component of course CS F317 - Reinforcement Learning
### Report : Link
## Tools used
- Java 1.8.0 or higher
- Ant 1.9.3 or higher
- Node 0.10.25 or higher
- Google Colab

## Downloads
1. Clone this repository: `git clone https://github.com/saandra02/DRL-dialogue.git`
2. Download Pretrained vectors for word embedding from http://nlp.stanford.edu/data/glove.6B.zip and put the desired file in DRL-dialogue/resources/english/

## Compilation and Execution
1. `cd YourPath/DRL-dialogue`
2. `ant`
3. Server side: `cd YourPath/DRL-dialogue` then `ant SimpleDS`
<img width="1440" alt="Training - server side" src="https://user-images.githubusercontent.com/24243373/144218813-86d68220-a150-4ada-bf1a-c02b7cc39f8f.png">
5. Client Side: `cd YourPath/DRL-dialogue/web/main` then `nodejs runclient.js (train|test) [num_dialogues] [-v|-nv]`
<img width="1440" alt="Training - client side" src="https://user-images.githubusercontent.com/24243373/144218944-e1823735-a228-4edf-a13c-d22eed101c46.png">

## Plotting
Output and policy is generated in DRL-dialogue/results as a .txt and .json file respectively. Results were analyzed and graphs were plotted using Google Colab.

## Config file
The config file present in DRL-dialogue/config.txt has number of paramenters which can be changed to experiment with diffrent values. 
