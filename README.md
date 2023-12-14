# ETL_data_Results
Data processing and obtaining information from the Dataset
This experiment collects specific data from the dataframe, but first performs the necessary processing on the data to obtain the information.

# ETL_dados_Resultados
Data processing and obtaining information from the Dataset(Tratamento de dados e obtenção de informações do Dataset)
Esta experiência coleta dados específicos do dataframe, mas antes faz o tratamento necessário nos dados para obter as informações.

df.groupby(by='windspeed')
media = df['windspeed'].mean()
media = df['temp'].mean()
df['datetime'] = pd.to_datetime(df['datetime'])

More...
Saiba mais...
