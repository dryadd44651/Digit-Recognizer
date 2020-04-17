# Digit-Recognizer

Using CNN(Keras) to solve classification of handwritten images




For accelerating the test. I set the test_size to 0.8, epochs to 3 and only using the small dataset.
Normal training setting should be test_size=0.1 epochs = 30

train_history = model.fit(x_train, y_train, batc_size=200,epochs=3,callbacks=[learning_rate_function],validation_data = (x_val,y_val))
train_test_split(x_train, y_train, test_size = 0.8, random_state=random_seed

https://www.kaggle.com/c/digit-recognizer
