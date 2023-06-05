# pet_project_templates

# задаем параметры функции 

```countries = ["USA", "GBR"]
indicators = ["SP.POP.TOTL", "NY.GDP.MKTP.CD"]
start_date = "2015"
end_date = "2020"

data = request_world_bank_data(countries, indicators, start_date, end_date)

df = create_df(data)
df```

![Alt text](result.png?raw=true "Optional Title")