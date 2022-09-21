SET mystNumb TO 2
SEND 'Please enter guess number' TO DISPLAY
RECEIVE guess FROM KEYBOARD
IF guess > 10 THEN
SEND 'Too high! Your guess must be between 1 and 10' TO DISPLAY
  ELSE
  IF guess = mystNumb THEN
  SEND 'Well done! You guess correctly' TO DISPLAY
    ELSE
    SEND 'Back luck! The correct number is' = mystNumb TO DISPLAY
    IF END
  IF END
IF END
END
