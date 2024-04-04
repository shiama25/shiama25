public static void main(String[] args) {
        Account c1=new Account("Ali");
        Account c2=new Account("shaima",700,"programmer","femal");
        Account c3=new Account(700);
        Account c4=new Account("suha",100.000,"dr");
        System.out.println(c1);
        System.out.println(c2);
        System.out.println(c3);
        System.out.println(c4);
        System.out.println(c1.netSalary(100,18));
        System.out.println(c2.netSalary(33,22));
        System.out.println(c3.netSalary(70,45));
                System.out.println(c4.netSalary(50,21));

        
    }
    
}
