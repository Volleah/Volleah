```
                                               /((                              
                                     ((%%%%(   **/(                               
                                  (///*****/** ,,*,,,,*/ &((#                    
                                 ///*,,,,,/**,,...,*,,///(/%                        
                                 /**/(*/*/((,...... ..,,,*(                    
                                /**//,...    ,*,*,...,,,*/                      
                                /***,,...       ...,,*/                              
                                (/*,,....      ..,*                                  
                                 (//,....    .....*                                
                                    /***,,,...,***                                 
                                     *,***// (/**,                               
                                     (**,%   //,,,                     
                                      (///   *. .                          
                                      ,,*,/  *,,*                
                                             *...                  
                                             *,,,*      
                                                                                
```
```c#
class GithubInfo
{
    private int Age;
    private string Name;
    private string[] Languages;
    private string MainLanguage;
    public GithubInfo(int Age, string Name, string[] Languages, string MainLanguage)
    {
        this.Age = Age;
        this.Name = Name;
        this.Languages = Languages;
        this.MainLanguage = MainLanguage;
    }
    public void Introduction()
    {
        Console.WriteLine("Hello all! my name is " + Name + ", I'm an " + Age + " year old high-school student independently studying computer science.");
        Console.WriteLine("");
        Console.WriteLine("I mostly program in " + MainLanguage + ", but I am confident with programming in any of these languages:");
        foreach (string language in Languages)
        {
            Console.WriteLine(language);
        }
        Console.WriteLine("I hope you find something interesting on my profile :)");
        Console.WriteLine("Have a wonderful day!");
    }
}
class Program
{
    public static void Main(string[] args)
    {
        GithubInfo AyhamInfo = new GithubInfo(18, "Ayham", new string[] { "C#", "SQL", "Java", "JavaScript", "HTML" }, "C#");
        AyhamInfo.Introduction();
    }
}
```                                                                               
