```java
public record ShashiSharma(
    String role,
    String email,
    String linkedin,
    List<String> techStack
) {

    public static ShashiSharma getDeveloper() {
        return new ShashiSharma(
            "BACKEND ENGINEER",
            "shashimaven2.0@gmail.com",
            "https://www.linkedin.com/in/shashi-kumar-sharma-67a843144/",
            List.of("Java", "Spring Boot", "Redis", "Kafka", "Docker")
        );
    }

}


### 📫 How to reach me

🔗 LinkedIn: [Shashi Sharma](https://www.linkedin.com/in/shashi-kumar-sharma-67a843144/)
📧 Email: shashimaven2.0@gmail.com
