<!--
**shuchu/shuchu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Hi there 👋
last update: April-23-2024

### Feast.dev 
Good News, The Feast project is back to normal running status. Here is a doc about the plan: https://docs.google.com/document/d/1DgtDmLCBnXQF9qva9X6Vac2ehpplj2iz6ZYw76NL8gM/edit?usp=sharing
Everything is back to normal since we have new maintainers and reviewers. Thanks, Redhat and Affirm!!

#### Tasks Queue 
1. (done) ~~FeatureView name conflicts between streaming Featureview and regular FeatureView:~~ [#3836](https://github.com/feast-dev/feast/issues/3836),[#3805](https://github.com/feast-dev/feast/issues/3805)
2. (done) ~~SnowFlake Feature Store requires READ-only property, as there is an unnecessary "CREATE Table" logic over there.~~ [#3844](https://github.com/feast-dev/feast/issues/3844)
3. (done) ~~Pydantic 2.0 upgradation.~~ [#3778](https://github.com/feast-dev/feast/issues/3778)
3. (done) ~~protobuf crash at higher version that 4.23.4.~~ [#3921](https://github.com/feast-dev/feast/issues/3921)

### Feast Feature Server Improvements
After few discussion among the maintainers, we decided to have the following plan for Feast feature server:   
1, Work on the Python version of featuer server first. Focus on reducing the latency.   
2, Fix the Java version. drop transformation service for odfvs.   
3, remove the Apache Arrow library dependecies from the code.    

My current plan of reducing the latency of Python Feature Server.   
1, Modify the existing benchmark code to run it locally.    
2, Build a Helm chart for deploy a Feast Feature Server to k8s.   
3, Add the monitor metrics and traces.   
4, Evaluation.   
5, (TBD) optimization directions: using asnyc
6, Improve the peformance of using Redis as online feature store.   
   Related tickets:
   https://github.com/feast-dev/feast/issues/3596
   https://github.com/feast-dev/feast/issues/4133

#### Backlog
1. Improve the Logging feature of Feast.
2.  "Go" Feature server improvement. [#3998](https://github.com/feast-dev/feast/issues/3998)


<!--
#### Misc:
1. MIT 6.824 course project
2. C++ server-side programming practice.
3. LangChain (RAG only)
-->


