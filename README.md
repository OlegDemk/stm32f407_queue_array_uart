# stm32f407_queue_array_uart

Simple queue based on array. For inpun/output using UART3. 
Items on the Queue can be dequeue/enqueue manually.

//------------------------------------------------------------
  print_text("--	QUEUE	--\n\r");
  
  show();
  dequeue();
  enqueue(1);
  enqueue(2);
  enqueue(3);
  enqueue(7);
  enqueue(7);
  show();
  dequeue();
  show();
//------------------------------------------------------------
