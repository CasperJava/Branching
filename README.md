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
