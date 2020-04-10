*Anonymous Class* 
   <br/> Anonymous classes enable you to make your code more concise. They enable you to declare and instantiate a class at the same time.
   <br/> Ex:
    <br/>Runnable runnable = new Runnable() {
            @Override
            public void run() {
                System.out.println("Inside : " + Thread.currentThread().getName());
            }
        };

<br/> in java 8
<br/>Runnable runnable = () -> {
            System.out.println("Inside : " + Thread.currentThread().getName());
        };
        
        
