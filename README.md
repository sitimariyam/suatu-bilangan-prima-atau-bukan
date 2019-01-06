# suatu-bilangan-prima-atau-bukan


    #include<iostream>
    using namespace std;

    main()
    {
    int x,i,count=0;
    cout<<"\nMasukkan sebuah angka : ";
    cin>>x;
    for(i=2;i<=x/2;i++)
    {
    if(x%i==0)
    count++;
    }
    if(count>0 || x<2)
    cout<<x<<" bukan bilangan prima\n";
    else
    cout<<x<<" bilangan prima\n";
    }
