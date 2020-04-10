*Anonymous Class* 
    Anonymous classes enable you to make your code more concise. They enable you to declare and instantiate a class at the same time.
    Ex:
    Runnable runnable = new Runnable() {
            @Override
            public void run() {
                System.out.println("Inside : " + Thread.currentThread().getName());
            }
        };
        
        
