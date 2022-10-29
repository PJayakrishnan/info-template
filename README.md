# info-template README
---

Add various information templates with ease in VSCode by installing Info Template extension..

## Features
---

You can insert various information templates just by typing the prefix and `Tab` when working in C++ and C#.

## C++ Snippets

| Prefix           |  What you get                      |
|------------------|------------------------------------|
| !fit             |  [File Information Template]()     |
| !mit             |  [Method Information Template]()   |
| !cpp_boilerplate |  [Cpp Hellow world Boilerplate]()  |
| !read_array      |  [Read array from console in C++]()|

<br>

## C# Snippets

| Prefix              |  What you get                        |
|---------------------|--------------------------------------|
| !fit                |  [File Information Template]()       |
| !mit                |  [Method Information Template]()     |
| !csharp_boilerplate |  [Csharp Hellow world Boilerplate]() |
| !read_array         |  [Read array from console in C#]()   |


<br>

<details>
    <summary>File Information Template</summary>
    <br>

    //*****************************************************
    // File Name    :
    // Author       :
    // Last Updated :
    //*****************************************************

</details>

<details>
    <summary>Method Information Template</summary>
    <br>

    //*****************************************************
    // Method name :
    // Return type :
    // Parameters  :
    // Note        :
    //*****************************************************


</details>

<details>
   <summary>Cpp Hellow world Boilerplate</summary>
   <br>

    #include<iostream.h>

    int main()
    {
        std::cout << "Hello world!!";
        return 0;
    }

</details>

<details>
   <summary>CSharp Hellow world Boilerplate</summary>
   <br>

    namespace HelloWorld
    {
        class Hello 
        {         
            static void Main(string[] args)
            {
                System.Console.WriteLine("Hello World!");
            }
        }
    }


</details>

<details>
   <summary>Read array from console in C++</summary>
   <br>

    for(int i = 0 ; i < size ; i++)
    {
        std::cin >> array[i];
    }

</details>


</details>

<details>
   <summary>Read array from console in C#</summary>
   <br>

    for(int i = 0 ; i < size ; i++)
    {
        arr[i] = Convert.ToInt32(Console.ReadLine());
    }

</details>

<br>


## 1.0.3


**Enjoy!**
