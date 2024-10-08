```csharp
namespace PersonalInformation
{
    class Program
    {
        static void Main(string[] args)
        {
            GeneralInfo general = new GeneralInfo
            {
                Name = "Luna Guadarrama Kitzya Minerva",
                Age = 19,
                Birthday = new DateTime(2004, 11, 26),
                Hobbies = new List<string> { "Hacer chistes de mis amigos", "Escucahr Musica" }
            };

            Education studies = new Education
            {
                Institute = "IPN",
                MiddleHighSchool = new MiddleHighSchool
                {
                    School = "CECyT 13 Ricardo Flores Magon",
                },
                HighSchool = new HighSchool
                {
                    School = "UPIICSA",
                    Career = "Ingeneria en Informatica",
                    Status = "5to Semestre"
                }
            };

            ProgrammingKnowledge programmingKnowledge = new ProgrammingKnowledge
            {
                Languages = new List<string> { "C", "C++","JavaScript","PHP" },
                Frameworks = new Frameworks
            };

            OtherSkills otherSkills = new OtherSkills
            {
                Databases = new List<string> { "SQL Server"},
                DesignTools = new List<string> { "Figma" },
                {
                    Word = true,
                    PowerPoint = true,
            };
     }       
}
```