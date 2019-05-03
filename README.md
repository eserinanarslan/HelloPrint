# helloprint

This project was developed for "HELLOPRINT"

HelloPrint project is a streaming data architecture that collects events from JSON files and persists events on targets (SQLITE).

When the project was developed, it was observed that the parameters of continuous data were increased and the data structure was developed accordingly.

Architucture:

<img width="518" alt="Screen Shot 2019-05-03 at 19 49 25" src="https://user-images.githubusercontent.com/25620152/57152609-a3cf1100-6ddc-11e9-96bf-77e5f0bb31b4.png">

Tool Used:
Pycharm Community 2019.1
SQLITE
Python 3.6

Asistant Tools:
"watch" for controlling DB. You have to install "watch" to your computer. (brew install watch)

Execution:

- First of all you have to install requirements by using below command under HelloPrint project.
pip install -r requirement.txt 

- Secondly you have to put source json files under with below hierarchy:

![Screen Shot 2019-05-03 at 19 46 42](https://user-images.githubusercontent.com/25620152/57152501-5ce11b80-6ddc-11e9-8681-9c7f06b7c64a.png)

- Then you can app.py file.
Python src/app.py

![Screen Shot 2019-05-03 at 19 35 17](https://user-images.githubusercontent.com/25620152/57152322-d75d6b80-6ddb-11e9-9b18-43fa5a709db6.png)
