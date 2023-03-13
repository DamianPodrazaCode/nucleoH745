/*
 * loop.c
 *
 *  Created on: Mar 9, 2023
 *      Author: ZoMbiE
 */

#include "loopCM7.h"

void setup() {
}

void loop() {
//		HAL_GPIO_TogglePin(TEST_GPIO_Port, TEST_Pin);  // 90ns
//		HAL_GPIO_TogglePin(TEST_GPIO_Port, TEST_Pin);
//		HAL_GPIO_TogglePin(TEST_GPIO_Port, TEST_Pin);
//		HAL_GPIO_TogglePin(TEST_GPIO_Port, TEST_Pin);

//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 0); // 60ns
//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 1);
//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 0);
//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 1);
//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 0);
//		HAL_GPIO_WritePin(TEST_GPIO_Port, TEST_Pin, 1);

		TEST_GPIO_Port->BSRR |= TEST_Pin;			//50ns
		TEST_GPIO_Port->BSRR |= TEST_Pin << 16;
		TEST_GPIO_Port->BSRR |= TEST_Pin;
		TEST_GPIO_Port->BSRR |= TEST_Pin << 16;
		TEST_GPIO_Port->BSRR |= TEST_Pin;
		TEST_GPIO_Port->BSRR |= TEST_Pin << 16;
		TEST_GPIO_Port->BSRR |= TEST_Pin;
		TEST_GPIO_Port->BSRR |= TEST_Pin << 16;
}

