### 👨‍💻 Developer Profile

```csharp
namespace PerfilDoDev
{
    public class DevIniciante : Humano
    {
        public string Nome { get; set; } = "Lucas Soler Chanhi";
        public string[] Hobbies { get; set; } = new string[] { "League of Legends", "Manga", "Coding" };
        public string FocoAtual { get; set; } = "Backend .NET & TCC OmniMarket";

        public void StackAtual()
        {
            // O que estou estudando e usando agora
            var skills = new List<string>
            {
                "C# / .NET 9.0",
                "Entity Framework",
                "Azure Cloud",
                "SQL Server"
            };
        }

        public string Objetivo()
        {
            return "Dominar a arquitetura de microsserviços e Web APIs.";
        }
    }
}
