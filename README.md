
![logo](https://github.com/bendevtech16/bendevtech16/assets/116570969/5fb7ebaf-5955-4b5f-ad48-6ca2d0eb5014)

                                        always busy, always on the grind

### Hi there 👋


package com.Bendevtech;

public class BenDevTech implements AwesomeProgrammer {
    private final String fullFirstName = "Benjamin";
    private final String university = "University of yaounde 1 (Cameroon)";
    private final String degree = "Bachelor degree";
    private final String workPlace = "CS Consulting";

    private String currentFocus = "Full stack Developer";

    enum BenStack {
        JAVA, ANGULAR, JS, TS, JPA, MVC, SQL, SPRINGBOOT, JUINT4, CRUD, REST,SOAP,GRAPHQL, ANDROID/IONIC
    }

    public String languagesISpeak(String environment) {
        switch (environment) {
            case "French":
                return "french";
            case "English":
                return "english";
            default:
                return "French";
        }
    }

    public ArrayList<String> activities() {
        return new ArrayList<>(Arrays.asList(
                "Productivity nerd",
                "Language enthusiast",
                "Crypto/stock investor"));
    }
}

