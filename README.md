### Hi there 👋

- 🔭 I’m currently working on a Humanitarian Poverty Web App.
- 🌱 I’m currently learning Javascript and React.
- 👯 I’m looking to collaborate on Anything that is out there to improve on human lives.
- 🤔 I’m looking for help with Competitive Programming.
- 💬 Ask me about anything related with technology.
- 📫 How to reach me: oritorichie2@gmail.com
- ⚡ Fun fact: Living healthy is an art you should try it.

## My Profile. 

``` Java

// Developer Information Object
import java.util.HashMap;
import java.util.Map;

public class DeveloperInfo {
    public static void main(String[] args) {
        // Developer Information Object
        Map<String, Object> developer = new HashMap<>();
        developer.put("name", "Orito");
        developer.put("age", 20);

        Map<String, String> hobbies = new HashMap<>();
        hobbies.put("general", "Health & Fitness");
        hobbies.put("sports", "Football");
        hobbies.put("dreams", "Travelling the World");
        hobbies.put("usedTo", "Being up all Night chasing that ONE BUG...");
        developer.put("hobbies", hobbies);

        String[] goals = {
            "🚀 Become a FullStack Web Developer",
            "🌍 Create a Humanitarian Aid Web App",
            "💡 Complete 100 JavaScript/TypeScript Projects",
            "👨🏼‍💻 Ask me for more of my goals!"
        };
        developer.put("goals", goals);

        // Output Developer Information
        System.out.println("Name: " + developer.get("name"));
        System.out.println("Age: " + developer.get("age"));
        System.out.println("Hobbies:");
        Map<String, String> hobbiesMap = (Map<String, String>) developer.get("hobbies");
        for (Map.Entry<String, String> entry : hobbiesMap.entrySet()) {
            System.out.println("  " + entry.getKey() + ": " + entry.getValue());
        }
        System.out.println("Goals:");
        String[] goalsArray = (String[]) developer.get("goals");
        for (int i = 0; i < goalsArray.length; i++) {
            System.out.println("  " + (i + 1) + ". " + goalsArray[i]);
        }
    }
}

```
#
[![alt text](https://img.shields.io/badge/-LinkedIn-0e76a8?style=plastic&logo=linkedIn)</a>](https://www.linkedin.com/in/richie-orito/)

**RichieOrito/RichieOrito** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
