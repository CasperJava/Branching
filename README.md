# Branching

// Задача № 1
        // Даны два угла треугольника (в градусах). Определить, существует ли
        // такой треугольник, и если да, то будет ли он прямоугольным.
        double degrees1 = 45.0;
        double degrees2 = 60.0;
        if ((degrees1 + degrees2) < 180) {
            System.out.println("Треугольник существует");
            if ((degrees1 + degrees2) == 90) {
                System.out.println("Треугольник прямоугольный");
            } else {
                System.out.println("Треугольник непрямоугольный");
            }
        } else {
            System.out.println("Треугольник не существует");
        }

// Задача № 2
        // Найти max{min(a, b), min(c, d)}.
        int a = 20;
        int b = 22;
        int c = 15;
        int d = 40;
        int min1;
        int min2;
        int max;
        if (a < b) {
            min1 = a;
        } else {
            min1 = b;
        }
        if (c < d) {
            min2 = c;
        } else {
            min2 = d;
        }
        if (min1 > min2) {
            max = min1;
        } else {
            max = min2;
        }
        System.out.println("max= " + max);

// Задача № 3
        // Даны три точки А(х1,у1), В(х2,у2) и С(х3,у3).
        // Определить, будут ли они расположены на одной прямой.
        double x1 = 1.0;
        double y1 = 1.0;
        double x2 = 3.0;
        double y2 = 3.0;
        double x3 = 6.0;
        double y3 = 6.0;
        if ((x3 - x1) / (x2 - x1) == (y3 - y1) / (y2 - y1)) {
            System.out.println("Точки А, B, C расположены на одной прямой");
        } else {
            System.out.println("Точки А, B, C не расположены на одной прямой");
        }
        
// Задача № 4
        // Заданы размеры А, В прямоугольного отверстия 
        // и размеры х, у, z кирпича.
        // Определить, пройдет ли кирпич через отверстие.
        int a = 70;
        int b = 125;
        int x = 250;
        int y = 120;
        int z = 65;
        if (x <= a && y <= b || y <= a && x <= b
                || x <= a && z <= b || z <= a && x <= b
                || z <= a && y <= b || y <= a && z <= b) {
            System.out.println("Кирпич пройдет через отверстие");
        } else {
            System.out.println("Кирпич не пройдет через отверстие");
        }
