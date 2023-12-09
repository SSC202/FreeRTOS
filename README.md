# STM32_FreeRTOS
本库介绍了 STM32 中实时操作系统 FreeRTOS 的基本用法，与源码 FreeRTOS 不同，本库结合 STM32CubeMX 介绍了 FreeRTOS 的 CMSIS V1/V2 封装，相对于源码更加简洁。

## 使用此库的前置条件

1. 学习了STM32的基本驱动方式，着重了解中断。[Click Here](https://github.com/SSC202/STM32_Basic)
2. 掌握 OLED 的基本驱动。

## 对应Note和相关Code说明

| Note                                                         | Note说明                                                     | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [1_FreeRTOS简介和配置](https://github.com/SSC202/FreeRTOS/tree/main/Note/1_FreeRTOS简介和配置) | 介绍FreeRTOS及其命名规范                                     |                                                              |
| [2_任务](https://github.com/SSC202/FreeRTOS/tree/main/Note/2_任务) | 介绍任务（`Task`）/线程的概念                                | 1. [创建任务实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/1_Task_Create) 2. [任务延时实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/2_Task_Delay) 3. [任务挂起实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/3_Task_Suspend) |
| [3_队列](https://github.com/SSC202/FreeRTOS/tree/main/Note/3_队列) | 介绍队列（`Queue`）的概念                                    | 1. [队列实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/4_Queue) 2. [信号通知实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/9_Signal) 3. [内存池实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/10_Pool) 4. [邮箱队列实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/11_Mail) |
| [4_信号量](https://github.com/SSC202/FreeRTOS/tree/main/Note/4_信号量) | 介绍信号量（`Semaphore`），互斥锁（`Mutex`），计数信号量（`Count`） | 1. [二值信号量实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/5_Binary_Semaphore) 2. [互斥信号量实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/6_Mutex_Semaphore) 3. [计数信号量实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/7_Count_Semaphore) |
| [5_事件标志组](https://github.com/SSC202/FreeRTOS/tree/main/Note/5_事件标志组) | 介绍事件标志组（`Event`）                                    | 1. [事件标志组实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/8_Event) |
| [6_软件定时器](https://github.com/SSC202/FreeRTOS/tree/main/Note/6_软件定时器) | 介绍软件定时器                                               | 1. [软件定时器实验](https://github.com/SSC202/FreeRTOS/tree/main/Code/12_Software_Timer) |
| [7_中断管理](https://github.com/SSC202/FreeRTOS/tree/main/Note/7_中断管理) | 介绍FreeRTOS的中断管理                                       |                                                              |

## 后续补充

1. FreeRTOS 的源码移植
2. FreeRTOS 的内存管理
