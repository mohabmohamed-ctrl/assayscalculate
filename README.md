#include<iostream>

using namespace std;

class assays_project{
    public:
    void items1()
    {
        string item1;
        string item2;
        string item3;
        cout<<"please enter name of items:"<<endl;
        cin>>item1;
        cin>>item2;
        cin>>item3;

        float salary1;
        float salary2;
        float salary3;
        
        cout<<"============================"<<endl;
        cout<<"okay enter salarys of this items:"<<endl;
        cin>>salary1;
        cin>>salary2;
        cin>>salary3;
        cout<<"============================="<<endl;
        cout<<"okay we will sum the prices of raw materials "<<endl;
        cout<<"salary of "<< item1 << " is:"<<salary1<<endl;
        cout<<"salary of "<< item2 <<" is:"<<salary2<<endl;
        cout<<"salary of "<< item3 << " is:"<<salary3<<endl;

        
        float total1;
        total1 = salary1 + salary2 + salary3;
        float initial_cost1;
        float five1;
        float hundred1;
        cout<<"total of materials is:"<<total1<<endl;
        float hours1;
        cout<<"enter the salary of employees , enter hours to complete this maintenance:"<<endl;
        cin>>hours1;
        cout<<" hour = 50 egp , total:"<<hours1*50<<endl;
        float salary_of_raw_materials;
        cout<<"okay enter salary of  raw materilas:"<<endl;
        cin>>salary_of_raw_materials;
        float salary_of_employee;
        cout<<"okay enter salarys of employee: "<<endl;
        cin>>salary_of_employee;
        
        float salary_of_initial_cost =  salary_of_raw_materials + salary_of_employee;
        
        cout<<"total is:"<<salary_of_initial_cost<<endl;


        
        cout<<"==============================="<<endl;
        cout<<"there is Indirect expenses: 5% of the price of raw materials and wages, which is the initial cost , calculate this:"<<endl;
        cout<<" calculate the indirect expenses: "<<endl;
        cout<<"======================================"<<endl;
        cout<<"initial cost is:";
        cin>>initial_cost1;
        cout<<"then:";
        cin>>five1;
        cout<<"then:";
        cin>>hundred1;
        float the_indirect_expenses1 = initial_cost1 * five1 / hundred1;
        cout<<"okay the calculate you have been from indirect expenses is:"<< the_indirect_expenses1<<endl;
        cout<<"================================================================"<<endl;
        cout<<"okay then we want to calculate the initial cost and indirect expenses,which production cost:"<<endl;

        

        float initial_cost2;
        float indirect_expenses2;
        
        cout<<"enter the initial cost salary:";
        cin>>initial_cost2;
        cout<<"okay enter the indirect expenses:";
        cin>>indirect_expenses2;
        float production_cost1 = initial_cost2+indirect_expenses2;
        cout<<"======================================================"<<endl;
        cout<<"then the total of production cost is:"<<production_cost1<<endl;
        cout<<"======================================================="<<endl;
        cout<<"then next there is a 10% of profits from production cost,then calculate them:"<<endl;
        
        float production_cost2;
        float ten1;
        float hundred2;
        cout<<"production cost salary is:";
        cin>>production_cost2;
        cout<<"then:";
        cin>>ten1;
        cout<<"then:";
        cin>>hundred2;
        float profits1 = production_cost2 * 10 / 100;
        cout<<"============================================="<<endl;
        cout<<"okay then the total of profits is:"<<profits1<<endl;
        cout<<"====================================="<<endl;
        cout<<"then next we want to calculate the end of production cost which profits plus production cost:"<<endl;
        float production_cost3;
        float profits2;
        float end_of_production_cost = production_cost3 + profits2 ;
        cout<<"enter the cost of production cost:";
        cin>>production_cost3;
        cout<<"enter the cost of profits cost:";
        cin>>profits2;
        cout<<"============================================="<<endl;
        cout<<"then the total of end of production cost is :"<<end_of_production_cost;
        cout<<endl;
        cout<<"then we are we complete the claculate assyas i hope you enjoy the calculating "<<endl;





       


        
    }
};
     

     class assays_project2{
        public:
        void items2(){

            string item4;
            string item5;
           string item6;
            string item7;
            string item8;
            cout<<"enter names of items:"<<endl;
            cin>>item4;
            cin>>item5;
            cin>>item6;
            cin>>item7;
            cin>>item8;
            cout<<"======================================="<<endl;

            float salary4;
            float salary5;
            float salary6;
            float salary7;
            float salary8;
            cout<<"okay enter salarys of items:"<<endl;
            cin>>salary4;
            cin>>salary5;
            cin>>salary6;
            cin>>salary7;
            cin>>salary8;


            
        cout<<"============================="<<endl;
        cout<<"okay we will sum the prices of raw materials "<<endl;
        cout<<"salary of :"<<item4<<" is :"<<salary4<<endl;
        cout<<"salary of "<< item5 <<" is:"<<salary5<<endl;
        cout<<"salary of "<< item6 << " is:"<<salary6<<endl;
        cout<<"salary of:"<< item7 << " is :"<<salary7<<endl;
        cout<<"salary of:"<< item8 << "is :"<<salary8<<endl;
        
            float total2 = salary4+salary5+salary6+salary7+salary8;
            cout<<"the total of materials is:"<<total2<<endl;


            
        float hours2;
        cout<<"enter the salary of employees , enter hours to complete this maintenance:"<<endl;
        cin>>hours2;
        cout<<" hour = 50 egp , total:"<<hours2*50<<endl;
        float salary_of_raw_materials3;
        cout<<"okay enter salary of  raw materilas:"<<endl;
        cin>>salary_of_raw_materials3;
        float salary_of_employee3;
        cout<<"okay enter salarys of employee: "<<endl;
        cin>>salary_of_employee3;
        
        float salary_of_initial_cost2 =  salary_of_raw_materials3 + salary_of_employee3;
        
        cout<<"total is:"<<salary_of_initial_cost2<<endl;
            

            
        float five5;
        float hundred3;
        float initial_cost6;
        cout<<"==============================="<<endl;
        cout<<"there is Indirect expenses: 5% of the price of raw materials and wages, which is the initial cost , calculate this:"<<endl;
        cout<<" calculate the indirect expenses: "<<endl;
        cout<<"======================================"<<endl;
        cout<<"initial cost is:";
        cin>>initial_cost6;
        cout<<"then:";
        cin>>five5;
        cout<<"then:";
        cin>>hundred3;
        float the_indirect_expenses4 = initial_cost6 * five5 / hundred3;
        cout<<"okay the calculate you have been from indirect expenses is:"<< the_indirect_expenses4<<endl;
        cout<<"================================================================"<<endl;
        cout<<"okay then we want to calculate the initial cost and indirect expenses,which production cost:"<<endl;

          float initial_cost7;
        float indirect_expenses7;
        
        cout<<"enter the initial cost salary:";
        cin>>initial_cost7;
        cout<<"okay enter the indirect expenses:";
        cin>>indirect_expenses7;
        float production_cost6 = initial_cost7+indirect_expenses7;
        cout<<"======================================================"<<endl;
        cout<<"then the total of production cost is:"<<production_cost6<<endl;
        cout<<"======================================================="<<endl;
        cout<<"then next there is a 10% of profits from production cost,then calculate them:"<<endl;

        float production_cost5;
        float ten3;
        float hundred4;
        cout<<"production cost salary is:";
        cin>>production_cost5;
        cout<<"then:";
        cin>>ten3;
        cout<<"then:";
        cin>>hundred4;
        
        cout<<"============================================="<<endl;
        float profits4 = production_cost5 * ten3 / hundred4;
        cout<<"okay then the total of profits is:"<<profits4<<endl;
        cout<<"====================================="<<endl;
        cout<<"then next we want to calculate the end of production cost which profits plus production cost:"<<endl;
        float production_cost4;
        float profits3;
        float end_of_production_cost4 = production_cost4 + profits3 ;
        cout<<"enter the cost of production cost:";
        cin>>production_cost4;
        cout<<"enter the cost of profits cost:";
        cin>>profits3;
        cout<<"============================================="<<endl;
        cout<<"then the total of end of production cost is :"<<end_of_production_cost4;
        cout<<endl;
        cout<<"then we are we complete the claculate assyas i hope you enjoy the calculating "<<endl;





            
        
            

        }


     };
     class assays_project3{
        public:
            void items3(){
         string item9;
            string item10;
           string item11;
            string item12;
            string item13;
            string item14;
            string item15;
            cout<<"enter names of items:"<<endl;
            cin>>item9;
            cin>>item10;
            cin>>item11;
            cin>>item12;
            cin>>item13;
            cin>>item14;
            cin>>item15;
            cout<<"======================================="<<endl;

            float salary9;
            float salary10;
            float salary11;
            float salary12;
            float salary13;
            float salary14;
            float salary15;
            cout<<"okay enter salarys of items:"<<endl;
            cin>>salary9;
            cin>>salary10;
            cin>>salary11;
            cin>>salary12;
            cin>>salary13;
            cin>>salary14;
            cin>>salary15;


            
        cout<<"============================="<<endl;
        cout<<"okay we will sum the prices of raw materials "<<endl;
        cout<<"salary of :"<<item9<<" is :"<<salary9<<endl;
        cout<<"salary of "<< item10 <<" is:"<<salary10<<endl;
        cout<<"salary of "<< item11 << " is:"<<salary11<<endl;
        cout<<"salary of:"<< item12 << " is :"<<salary12<<endl;
        cout<<"salary of:"<< item13 << "is :"<<salary13<<endl;
        cout<<"salary of:"<<item14 << "is :"<<salary14<<endl;
        cout<<"salary of:"<<item15 << " is :"<<salary15<<endl;
        
            float total3 = salary9+salary10+salary11+salary12+salary13+salary14+salary15;
            cout<<"the total of materials is:"<<total3<<endl;


            
        float hours3;
        cout<<"enter the salary of employees , enter hours to complete this maintenance:"<<endl;
        cin>>hours3;
        cout<<" hour = 50 egp , total:"<<hours3*50<<endl;
        float salary_of_raw_materials6;
        cout<<"okay enter salary of  raw materilas:"<<endl;
        cin>>salary_of_raw_materials6;
        float salary_of_employee10;
        cout<<"okay enter salarys of employee: "<<endl;
        cin>>salary_of_employee10;
        
        float salary_of_initial_cost11 =  salary_of_raw_materials6 + salary_of_employee10;
        
        cout<<"total is:"<<salary_of_initial_cost11<<endl;
            

            
        float five7;
        float hundred5;
        float initial_cost8;
        cout<<"==============================="<<endl;
        cout<<"there is Indirect expenses: 5% of the price of raw materials and wages, which is the initial cost , calculate this:"<<endl;
        cout<<" calculate the indirect expenses: "<<endl;
        cout<<"======================================"<<endl;
        cout<<"initial cost is:";
        cin>>initial_cost8;
        cout<<"then:";
        cin>>five7;
        cout<<"then:";
        cin>>hundred5;
        float the_indirect_expenses7 = initial_cost8 * five7 / hundred5;
        cout<<"okay the calculate you have been from indirect expenses is:"<< the_indirect_expenses7<<endl;
        cout<<"================================================================"<<endl;
        cout<<"okay then we want to calculate the initial cost and indirect expenses,which production cost:"<<endl;

          float initial_cost12;
        float indirect_expenses10;
        
        cout<<"enter the initial cost salary:";
        cin>>initial_cost12;
        cout<<"okay enter the indirect expenses:";
        cin>>indirect_expenses10;
        float production_cost7 = initial_cost12 +indirect_expenses10;
        cout<<"======================================================"<<endl;
        cout<<"then the total of production cost is:"<<production_cost7<<endl;
        cout<<"======================================================="<<endl;
        cout<<"then next there is a 10% of profits from production cost,then calculate them:"<<endl;

        float production_cost5;
        float ten5;
        float hundred7;
        cout<<"production cost salary is:";
        cin>>production_cost5;
        cout<<"then:";
        cin>>ten5;
        cout<<"then:";
        cin>>hundred7;
        float profits7 = production_cost5 * ten5 / hundred7;
        cout<<"============================================="<<endl;
        cout<<"okay then the total of profits is:"<<profits7<<endl;
        cout<<"====================================="<<endl;
        cout<<"then next we want to calculate the end of production cost which profits plus production cost:"<<endl;
        float production_cost10;
        float profits6;
       
        cout<<"enter the cost of production cost:";
        cin>>production_cost10;
        cout<<"enter the cost of profits cost:";
        cin>>profits6;
        cout<<"============================================="<<endl;
         float end_of_production_cost7 = production_cost10 + profits6 ;
        cout<<"then the total of end of production cost is :"<<end_of_production_cost7;
        cout<<endl;
        cout<<"then we are we complete the claculate assyas i hope you enjoy the calculating "<<endl;
            }
     };

int main()
{
    cout<<"======================== made by mohab ======================================="<<endl;
    cout<<"======================== welcome to calculate assays ========================="<<endl;

string  name;
    int item;
    cout<<"enter your name:"<<endl;
    cin>>name;
    cout<<"hello :"<<name<<endl;
    cout<<"=============================="<<endl;
    cout<<"here you have three options to calculate"<<endl;
    cout<<"1. 3 items to calculate "<<endl;
    cout<<"2. 5 items to calculate"<<endl;
    cout<<"3. 7 items to calculate"<<endl;
    cout<<"enter how much items do you want:"<<endl;
    cin>>item;

   
    switch(item)
    {
       assays_project ap;
        assays_project2 ap2;
        assays_project3 ap3;
        case 1:
         
        cout<<"================================"<<endl;
        
        ap.items1();

        break;
        case 2:
        ap2.items2();

        break;
        case 3:
        ap3.items3();
        break;
    }
    

}
