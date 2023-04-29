### Hi I'm Yamid 👋

```java

@Data
public class YamiDev {
    private String[] pronouns;
    private String[] code;
    private String[] tools;
}

public class Main {
    public static final Logger LOG = Logger.getLogger(Main.class.getName());
    public static void main(String[] args) {
        BasicConfigurator.configure();
        YamiDev yamiDev = new YamiDev();
        yamiDev.setPronouns(new String[] { "he", "him" });
        yamiDev.setCode(new String[] { "Java", "TypeScript", "HTML", "CCs" });
        yamiDev.setTools(new String[] { "Angular" ,"Spring-boot", "Git",
                                        "MySQL", "SQL Server", "Postgres Db" });
        LOG.info("YamiDev:");
        LOG.info("Pronouns: " + Arrays.toString(yamiDev.getPronouns()));
        LOG.info("Code: " + Arrays.toString(yamiDev.getCode()));
        LOG.info("Tools: " + Arrays.toString(yamiDev.getTools()));
    }
}

```

<!--
**YamithDev/YamithDev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=YamithDev)](https://github.com/YamithDev/github-readme-stats)
