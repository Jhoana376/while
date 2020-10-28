# while

Console.WriteLine();
            Console.WriteLine();
            System.Console.WriteLine("Programa que calcule el sueldo de los trabajadores semanal considerando que se les paga cierto porcentaje (%) segun su sueldo, se incrementa un porcentaje de prestaciones");

            #region declaracion de variables

            Double Stotal = 0;
            Double sueldo = 0;
            Double sueldo_1 = 0;
            Double sueldo_2;
            Double sueldo_3;
            Double sueldo_4;
            Double Nempleados = 0;
            Double sueldoN = 0;
            Double i = 1;

 #endregion

            System.Console.WriteLine("Ingrese el sueldo mensual del trabajador");
            sueldo = int.Parse(System.Console.ReadLine());
            sueldoN = sueldo * 12;
            System.Console.WriteLine("Ingrese el numero de empleados");
            Nempleados = int.Parse(System.Console.ReadLine());

            System.Console.WriteLine("El sueldo total es de {0}", sueldoN);
            sueldoN = int.Parse(System.Console.ReadLine());

        
            System.Console.WriteLine();
            System.Console.WriteLine("De acuerdo el sueldo ingresado, se aumentara cierto porcentaje al sueldo total");
            System.Console.ReadLine();

            while
              (sueldo <= 18000)
            {
                System.Console.WriteLine("Ingresa sueldo ", sueldo);
                sueldo = int.Parse(System.Console.ReadLine());

                sueldo_1 = sueldo * .12;
                i = i + 1;
            }
            System.Console.WriteLine("El sueldo total es de {0}", sueldo_1);

            while (18000 <= 30000) 
            {
                System.Console.WriteLine("Ingresa sueldo ", sueldo);
                sueldo = int.Parse(System.Console.ReadLine());

                sueldo_2 = sueldo * .8;
                i = i + 1;
            }
            System.Console.WriteLine("El sueldo total es de {0}", sueldo_2);

            while ( 30000 <= 50000) ;
            {
                System.Console.WriteLine("Ingresa sueldo ", sueldo);
                sueldo = int.Parse(System.Console.ReadLine());

                sueldo_3 = sueldo * .7;
                i = i + 1;
            }
            System.Console.WriteLine("El sueldo total es de {0}", sueldo_3);

            while (sueldo <= 50000) ;
            {
                System.Console.WriteLine("Ingresa sueldo ", sueldo);
                sueldo = int.Parse(System.Console.ReadLine());

                sueldo_4 = sueldo * .6;
                i = i + 1;
            }
            System.Console.WriteLine("El sueldo total es de {0}", sueldo_4);

            //Mostrar resultados por año //
            System.Console.WriteLine();
            System.Console.WriteLine("Mostrar sueldo total por año {0}", sueldoN);
            sueldoN = int.Parse(System.Console.ReadLine());


            System.Console.WriteLine("Ingrese el numero de empleados {0}", Nempleados);
            Nempleados = int.Parse(System.Console.ReadLine());
            Stotal = sueldoN * 12;

            System.Console.WriteLine("El sueldo calculado para el proximo año segun el numero de empleados ingresado es de {0}", Stotal);
            Stotal = int.Parse(System.Console.ReadLine());

            System.Console.ReadKey();

