# ml-pynb
For anyone getting an error related to converting a list to a float, the model.evaluate is actually returning a list. You just grab the first value in the list (which is why she puts [0]).  So change the line where you obtain the val_loss to:
