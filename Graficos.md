import matplotlib.pyplot as plt
import seaborn as sns 


#Barras na horizontal
plt.barh(valorx, valory) 
sns.barhplot(valorx, valory)

#Barras na vertical
plt.bar(valorx, valory) 
sns.barplot(valorx, valory) 

#Grafico de pizza
plt.pie(valor, label=identificação, radius= tamanho do grafico)
plt.show()

#Grafico de linhas
plt.plot(valorx, valory)




#identificando o grafico
plt.title('')
plt.xlabel('')  #size(#pode ser usado para escolher o tamanho do texto)
plt.ylabel('')
plt.show()
