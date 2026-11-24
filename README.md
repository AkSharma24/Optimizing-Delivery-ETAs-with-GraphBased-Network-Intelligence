### Optimizing Delivery ETAs with GraphBased Network Intelligence



Description:

Project is done To optimize ETA using Various Technique but Precisely in the Project we did EDA to know and clean our data identifying outliers and data visualization. then we tried to implement chokepoints and chronically delayed hubs. we tried to implement a Graph based approach to identify key metrics of our graph like in-degree,out-degree, centrality, clustering coefficient and to identify unique source hub and destination hub and unique nodes  1475 and 1491 unique edges and . then after doing this we tried to identify the bottle necks hubs and corridor and arranged them top 5 bottleneck.We then implemented baseline models Linear Regression,Random Forest,XGBoost to build Baseline Prediciton about ETA. their baseline ETA(+-15 of actual time was in the range(35,37). then after the building the baseline regression model we introduced graph based approch to find the embeddings using node2vec and GraphSage . to predict our ETA . The ETA by using node2vec was 47.03% ETA(+-15 of actual time for node2vec) and 41% for GraphSage NN based. after that we build XGBoostClassifier to predict Which route Type to build .Accuracy was 100% because we have used embeddings for it. 



Prerequisite:

jupyter-notebook

pandas

numpy

networkx

sklearn

node2vec

matplotlib

torch

xgboost



installation:

pip install <prerequisite-name>



Feature:

Can Predicted Expected time of arrival

Can Classify route-type ETA vs Carting



Contributing Guidelines

We love contributions! To keep things organized, please follow these steps when suggesting changes:



1\. \*\*Report Issues:\*\* Before writing any code, check the \[Issues] tab to see if your bug or feature request is already being discussed. If not, open a new issue.

2\. \*\*Fork the Repo:\*\* Click the "Fork" button at the top of this page to create your own copy of the project.

3\. \*\*Create a Branch:\*\* Create a descriptive branch name for your work:

```bash

&#x20;  git checkout -b feature/amazing-new-feature

4.Code Quality: Ensure your code is well-commented and matches the existing project style. If you are adding a machine learning model, please include the calculated accuracy metrics in your pull request description.



\## 📄 License



This project is licensed under the MIT License - see the \[LICENSE](LICENSE) file for details.



