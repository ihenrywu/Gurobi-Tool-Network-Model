# Gurobi Tool for Network Models

Gurobi is a renowned tool in decision optimization, yet its complexity often deters novices, particularly those without a background in programming. Thanks to [Zack Zhu](https://github.com/ziqianzhu), who created the [Gurobi-Optimization-Class-Tool](https://github.com/ziqianzhu/gurobi-optimization-class-tool/) to streamline Gurobi's usage for beginners. His tool enables users to input variables and constraints into an Excel sheet and then execute Gurobi via a Jupyter Notebook, making it particularly beneficial for educational settings. It allows students to concentrate on conceptual understanding rather than programming nuances. Building on Zack's foundation, I am pleased to introduce 2 tools specifically designed for optimization problems that require **Network Models**.

## TOOL 1: Excel to Gurobi for Network Models

Instead of manually inputting each variable and constraint, often a cumbersome task for Network Models, the tool [Excel_to_Gurobi_for_Network_Models.ipynb](https://github.com/ihenrywu/Gurobi-Tool-Network-Model/blob/main/%5BTOOL%201%5D%20Excel_to_Gurobi_for_Network_Models.ipynb) enables users to input only initial conditions, such as node names, inter-node relationships, and supply/demand data, into the Excel file [Excel_to_Gurobi_for_Network_Models.xlsx](https://github.com/ihenrywu/Gurobi-Tool-Network-Model/blob/main/Excel_to_Gurobi_for_Network_Models.xlsx). The code then autogenerates all relevant variables and constraints, minimizing the potential for human error and saving significant time.  

![Excel_to_Gurobi_for_Network_Models](https://github.com/ihenrywu/IMAGES/blob/main/Gurobi-Tool-Network-Model/screenshot%20of%20Excel%20file%20readme.png?raw=true)

Currently, the tool supports 6 different types of network model problems:

- Transportation Problem
- Transshipment Problem
- Assignment Problem
- Shortest Path Problem
- Maximum Flow Problem
- Traveling Salesperson Problem


Detailed usage guidelines can be found in: [Handbook of TOOL 1](https://github.com/ihenrywu/Gurobi-Tool-Network-Model/blob/main/%5BPDF%5D%20Handbook%20of%20TOOL%201.pdf).

**Note:** Execute Gurobi in Jupyter notebook need a Gurobi license and install Jupyter. Good news is that "Google Colab provides an easy way to use Gurobi with Python + Jupyter notebooks, with no local software installation required", and with no license needed. See the instructions [here](https://support.gurobi.com/hc/en-us/articles/4409582394769-Google-Colab-Installation-and-Licensing). For your convenience, I have also developed a Google Colab version of TOOL 1: [TOOL 1: Excel to Gurobi for Network Models(Google Colab Version)](https://colab.research.google.com/github/ihenrywu/Gurobi-Tool-Network-Model/blob/main/%5BTOOL%201%5D%20(Colab%20Version)%20Excel_to_Gurobi_for_Network_Models.ipynb)


## TOOL 2: Gurobi All-in-One Jupyter GUI

For those seeking an even more user-friendly experience, I have further good news: [Gurobi_All_in_One_Jupyter_GUI.ipynb](https://github.com/ihenrywu/Gurobi-Tool-Network-Model/blob/main/%5BTOOL%202%5D%20Gurobi_All_in_One_Jupyter_GUI.ipynb). This interactive version allows users to bypass Excel entirely. Instead, users can input initial conditions directly into a Jupyter Notebook, following on-screen prompts. The code then autogenerates the requisite variables and constraints and fetches the results from Gurobi. This iteration further simplifies the user interface and decreases the likelihood of errors.

![Gurobi All-in-One Jupyter GUI](https://github.com/ihenrywu/IMAGES/blob/main/Gurobi-Tool-Network-Model/screenshot%20of%20ipynb%20file.png?raw=true)

Detailed usage guidelines can be found in:[Handbook of TOOL 2](https://github.com/ihenrywu/Gurobi-Tool-Network-Model/blob/main/%5BPDF%5D%20Handbook%20of%20TOOL%202.pdf).

It's worth noting that these tools have a drawback: their ease of use allows users to obtain correct answers without fully grasping the underlying principles. While this could be a concern for educational contexts, the open-source nature of these tools provides a valuable opportunity for students to explore the practical applications of Gurobi and Jupyter further.

## Acknowledgments

I extend my heartfelt gratitude to [Professor Steven Shechter](https://www.sauder.ubc.ca/people/steven-shechter) and Zack, whose guidance and support have been indispensable in developing these tools.

>For any questions, feedback, or further discussion about these tools, please don't hesitate to reach out to me: [ihenrywu.ca#gmail.com]() or [LinkedIn](https://www.linkedin.com/in/ihenrywu/).