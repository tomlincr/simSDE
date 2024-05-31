# simSDE
A simulacrum of the [NHS Secure Data Environment](https://digital.nhs.uk/services/secure-data-environment-service), to facilitate education, exploration, external code development and testing.  

NB this is unofficial, and not endorsed by NHS England or HDR UK / BHF Data Science Centre.  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tomlincr/simSDE/blob/main/HES_APC_playground.ipynb)

# MVP
1. 🧑‍💻 Environment - Google Colab based for ease of use.
2. 💿 Synthetic data
    1. 🏥 Hospital Episode Statistics Admitted Patient Care: See [NHS Digital: Artificial data pilot](https://digital.nhs.uk/services/artificial-data). 

# Platform options
* [Databricks Community Edition](https://community.cloud.databricks.com/) ❌. 
    * Doesn't support Git. 
* Google Colab. ✅
    * Supports Spark
    * Poor Github integration - can open/save, but can't easily *sync*. 
    * Doesn't persist?
* [Github codespaces](https://github.com/codespaces) ❌
    * Flexible but too complex for beginners
    * https://aka.ms/configure-codespace. 
    * https://github.com/education/codespaces-project-template-py. 
* Local ❌
    * Way too complex for beginners!
    * Environment: pip, conda, ? poetry. 
    * Containers: docker, devcontainer. 
        * https://github.com/jplane/pyspark-devcontainer.  
        * Should be able to manage exactly the same as codespaces?

# Roadmap

1. [ ] Other HES datasets:  
    1. [ ] HES OP  
    2. [ ] HES A&E  
    3. [ ] HES CC (*NB not part of Artificial Data Pilot*)  
    4. [ ] HES MAT (*NB not part of Artificial Data Pilot*)  
1. [ ] Synthetic ONS Deaths.  
1. [ ] Synthetic GDPPR.  
