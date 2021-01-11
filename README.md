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
