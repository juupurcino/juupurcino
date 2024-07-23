import Developer.juupurcino;

public class About extends Developer {
    public String name = "Juliana Dias Purcino";
    public int age = 21;
    public String work = "Bosch";
    public String local = "Curitiba";
  
    public String college = "Software Engineering";
    public int semester = 3;

    public About() {
        super();
    }
}

import Developer.juupurcino;

public class Skills extends Developer {
    public String[] languages = { "Python", "C", "Java" };
    public String[] databases = { "SQL Server", "MySQL" };

    public Skills() {
        super();
    }
}
