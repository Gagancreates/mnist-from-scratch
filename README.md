# mnist from scratch

> built a neural net on MNIST using just numpy.

---

## what it does

- loads and preprocesses the dataset  
- builds a 2-layer neural network (`784 → 10 → 10`)  
- uses **ReLU + Softmax**  
- trains using **batch gradient descent**  
- tracks **loss + accuracy**  
- visualises predictions

---

## data

get `train.csv` from [kaggle digit recognizer](https://www.kaggle.com/competitions/digit-recognizer/data)  
put it in your working directory.

---

## requirements

- numpy  
- pandas  
- matplotlib

---

## sample output

- final accuracy ~76% on dev set  
- predictions visualised with actual labels  

---

> the goal was to understand what’s under the hood.  
> feel free to fork, tweak, or build on top of this.
