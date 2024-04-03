loss, accuracy = mobile.evaluate(test_dataset, steps = validation_steps)

print("--------MobileNet---------")
print("Loss: {:.2f}".format(loss))
print("Accuracy: {:.2f}".format(accuracy))
print("---------------------------")

loss, accuracy = res.evaluate(test_dataset, steps = validation_steps)

print("--------ResNet---------")
print("Loss: {:.2f}".format(loss))
print("Accuracy: {:.2f}".format(accuracy))
print("---------------------------")

loss, accuracy = dense.evaluate(test_dataset, steps = validation_steps)

print("--------DenseNet---------")
print("Loss: {:.2f}".format(loss))
print("Accuracy: {:.2f}".format(accuracy))
print("---------------------------")

<!---
yerramsettynikitha/yerramsettynikitha is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
