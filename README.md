# Intel-gyeonggi2
## Intel-gyeonggi2
### Intel-gyeonggi2
#### Intel-gyeonggi2
//int r = HAL_GPIO_ReadPin(BLUE_GPIO_Port, BLUE_Pin);
	  //if(r == 0)	//Button pushed
//	  if(val ==0)
//	  {
//		  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1);	//LED ON
//		  HAL_Delay(1000);								//delay 1 second
//		  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);	//LED OFF
//		  HAL_Delay(1000);								//delay 1 second
//	  }
//	  if(flag == 1)
//	  {
//	  for(int i=0;i<val;i++)
//	  {
//		  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1);	//LED ON
//		  HAL_Delay(1000);								//delay 1 second
//		  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);	//LED OFF
//		  HAL_Delay(1000);//delay 1 second
//		  flag = 0;
//	  }
//	  }
	  if(val ==0)
	  {
	  //HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1);	//LED ON
		HAL_GPIO_TogglePin(LD2_GPIO_Port, LD2_Pin);
		HAL_Delay(200);
	  }
	  else
	  {
	  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);	//LED OFF
	  }
