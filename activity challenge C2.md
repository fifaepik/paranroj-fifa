SEND 'Please enter your height' TO DISPLAY
RECEIVE height FROM KEYBOARD
SEND 'Please enter your weight' TO DISPLAY
RECEIVE weight FROM KEYBOARD
SET BMI to weight/height^2
IF BMI <18.5 THEN
  SEND 'You're underweight' TO DISPLAY
  ELSE
  IF BMI <=24.9 THEN
    SEND 'You're normal weight' TO DISPLAY
    ELSE
    IF BMI >=25 THEN
      SEND 'You're overweight' TO DISPLAY
    IF END
  IF END
IF END
END
