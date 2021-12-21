# SA2-resubmission

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        string name;
        int num;
        int fac = 1;
        int expo = 1;
        int pwresult = 1;
        int table = 0;


        cout << "Please enter your name: " << endl;
        getline(cin, name);


        cout << "Welcome " << name << "! Please enter a number!" << endl;
        cin >> num;



        //FACTORIAL
        for (int i = 1; i <= num; i++)
        {
            fac *= i;

        }
        cout << "\nThe factorial of " << num << " is " << fac << endl;


        //TABLE
        cout << "\nThe table of " << num << " from 1- 10 \n\n";
        int i = 1;
        do {
            cout << num << "x" << i << "=" << num * i << endl;
            i++;
        } while (i <= 10);

        //Square and Cube root

        for (cin.fail())
        {
            cout << "Invalid command enter the numbers again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> x;
        }

        cout << "The square-root of " << x << " is " << sqrt(x) << endl;
        cout << "The cube-root of " << x << " is " << cbrt(x) << endl;

        return 0;



    }
