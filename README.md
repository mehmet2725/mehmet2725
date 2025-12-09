# 👨‍💻 System.Console.WriteLine("Hello World!");

### User_Profile.cs

```csharp
namespace MehmetWorld
{
    public class Developer
    {
        public string Name { get; set; } = "Mehmet";
        public string Role { get; set; } = "Full-Stack Developer";
        
        public string[] CurrentFocus { get; set; } = 
        {
            "Clean Architecture",
            ".NET Core",
            "Next.js Performance"
        };

        public void SayHi()
        {
            Console.WriteLine("Kod yazmayı, kahveyi ve sınırları zorlamayı severim.");
        }
    }
}
