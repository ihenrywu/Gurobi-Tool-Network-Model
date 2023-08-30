# Gurobi Tool for Network Models

Gurobi is a renowned tool in decision optimization, yet its complexity often deters novices, particularly those without a background in programming. Thanks to [Zack](https://github.com/ziqianzhu), who created the [Gurobi-Optimization-Class-Tool](https://github.com/ziqianzhu/gurobi-optimization-class-tool/) to streamline Gurobi's usage for beginners. His tool enables users to input variables and constraints into an Excel sheet and then execute Gurobi via a Jupyter Notebook, making it particularly beneficial for educational settings. It allows students to concentrate on conceptual understanding rather than programming nuances.

## TOOL 1: Excel to Gurobi for Network Models

Building on Zack's foundation, I am pleased to introduce a specialized tool specifically designed for optimization problems that require network models: [Excel_to_Gurobi_for_Network_Models](). Instead of manually inputting each variable and constraint, often a cumbersome task for Network Models, this tool enables users to input only initial conditions, such as node names, inter-node relationships, and supply/demand data. The code then autogenerates all relevant variables and constraints, minimizing the potential for human error and saving significant time.  Currently, the tool supports 6 different types of network model problems:

- Transportation Problem
- Transshipment Problem
- Assignment Problem
- Shortest Path Problem
- Maximum Flow Problem
- Traveling Salesperson Problem


Detailed usage guidelines can be found in the accompanying Handbook: [Handbook of Excel to Gurobi for Network Models]().

## TOOL 2: Gurobi All-in-One Jupyter GUI

For those seeking an even more user-friendly experience, I have further good news: [Gurobi_All_in_One_Jupyter_GUI](). This interactive version allows users to bypass Excel entirely. Instead, they can input initial conditions directly into a Jupyter Notebook, following on-screen prompts. The code then autogenerates the requisite variables and constraints and fetches the results from Gurobi. This iteration further simplifies the user interface and decreases the likelihood of errors.

Detailed usage guidelines can be found in the accompanying Handbook:[Handbook of Gurobi All-In-One Jupyter GUI]().

It's worth noting that these tools have a drawback: their ease of use allows users to obtain correct answers without fully grasping the underlying principles. While this could be a concern for educational contexts, the open-source nature of these tools provides a valuable opportunity for students to explore the practical applications of Gurobi and Jupyter further.

## Acknowledgments

I extend my heartfelt gratitude to [Professor Steven Shechter](https://www.sauder.ubc.ca/people/steven-shechter) and Zack, whose guidance and support have been indispensable in developing these tools.

Let us all embrace the power and efficiency of Gurobi for making optimal decisions!

>For any questions, feedback, or further discussion about these tools, please don't hesitate to reach out to me: [ihenrywu.ca#gmail.com]() or [LinkedIn](https://www.linkedin.com/in/ihenrywu/).