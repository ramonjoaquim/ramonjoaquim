```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Bio: " + getBio());
        System.out.println("Daily Knowledge: " + Arrays.toString(getDailyKnowledge()));
        System.out.println("Future Goal: " + getFutureGoal());
    }

    public static String getBio() {
        return "Bachelor in Information System, Full Stack Developer with knowledge about DevOps culture, " +
                "API development and also functional and automated tests.";
    }

    public static String[] getDailyKnowledge() {
        return new String[]{
                "Java",
                "Angular",
                "Kubernetes",
                "Javascript",
                "MongoDB",
                "NestJS",
                "AWS",
                "GitLab",
                "React"
        };
    }

    public static String getFutureGoal() {
        return "To be a Java expert";
    }
}

