SEND 'Enter temperature' TO DISPLAY
RECEIVE temp FROM KEYBOARD
IF temp <18C THEN
  SEND 'Cold,the perfect temperature for sleep is 18-21 degrees.'
  IF temp >21C THEN
    SEND 'Pefect!' TO DISPLAY
    ELSE
      SEND 'No!, the perfect temperature for sleep is 18-21 degrees.'
   END IF
END IF
