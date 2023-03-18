# exerciseOneHotEncoding
# First i take the car models then i changed it into numerical data
# Then i put it into columns(pd.concat([df, dummies], axis = 'columns')
# drop first adn last column (merged.drop(["Car Model", "Mercedez Benz"], axis = "columns"))
# Separate column prices of rest of columns and put it into X and Y, finally train my model 
# So i can take the score and make predictions """model.predict([[86000,7,0,1]])""" , """model.score(X,Y)"""
