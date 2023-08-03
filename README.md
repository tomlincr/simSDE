# simSDE
A simulacrum of the NHS Secure Data Environment, to facilitate external code development &amp; testing

# MVP
1. Environment
2. Synthetic data
    1. Hospital Episode Statistics: See [NHS Digital: Artificial data pilot](https://digital.nhs.uk/services/artificial-data). 

# Platforms
* [Databricks Community Edition](https://community.cloud.databricks.com/) ❌. 
    * Doesn't support Git. 
* Google Colab. 
    * Supports Spark
    * Poor Github integration - can open/save, but can't easily *sync*. 
    * Doesn't persist?
* Github codespaces
    * https://github.com/education/codespaces-project-template-py. 
* Local
    * Environment: pip, conda, ? poetry. 
    * Containers: docker, devcontainer. 
        * https://github.com/jplane/pyspark-devcontainer. 


# Roadmap
1. [ ] Synthetic GDPPR. 
