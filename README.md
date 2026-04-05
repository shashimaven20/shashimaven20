public record shashi_sharma(
    String role,
    String email,
    String linkedin,
    List<String> techStack
) {

    public static shashi_sharma getDeveloper() {
        return new shashi_sharma(
            "BACKEND ENGINEER",
            "shashimaven2.0@gmail.com",
            "[🔗 LinkedIn: [shashi-sharma](https://www.linkedin.com/in/shashi-kumar-sharma-67a843144/)",
            List.of("Java", "Spring Boot", "Redis", "Kafka", "Docker")
        );
    }
}
