 //Presentation Layer:
 
 // This layer handles user interface and input/output operations
 using System;

 namespace PresentationLayer
 {
      class Program
      {
          static void Main(string[] args)
          {
              // Call methods from BusinessLogicLayer to perform operations
              Console.WriteLine(BusinessLogicLayer.GetData());
              Console.WriteLine(BusinessLogicLayer.Calculate(5,  10));
          }
      }
 }
 
//Business Logic Layer:

// This layer contains the business logic of the application
 using DataAccessLayer;

 namespace BusinessLogicLayer
 {
      public static class BusinessLogicLayer
      {
          public static string GetData()
          {
              // Call methods from DataAccessLayer to retrieve data
              return DataAccessLayer.GetData();
          }

          public static int Calculate(int a, int b)
          {
              // Perform calculations using data from DataAccessLayer
              return DataAccessLayer.GetTotal(a, b);
          }
      }
 }

//Data Access Layer:

 // This layer handles data storage and retrieval
 namespace DataAccessLayer
 {
      public static class DataAccessLayer
      {
          public static string GetData()
          {
              // Retrieve data from a database or other data source
              return "Hello, world!";
          }

          public static int GetTotal(int a, int b)
          {
              // Perform calculations and return results
              return a + b;
          }
      }
 }
