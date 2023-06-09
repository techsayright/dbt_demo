# dbt_demo

Welcome to your new dbt project!

### Using the starter project
at your home location it will create .dbt folder and under that folder it has profiles.yml file:
edit that file as:
dbt_demo:
  outputs:
    dev:
      account: tuvgewp-ni53286
      database: TEMP
      password: 
      role: 
      schema: PUBLIC
      threads: 10
      type: snowflake
      user: 
      warehouse: COMPUTE_WH	
  target: dev



Try running the following commands:
- dbt debug
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
