# MR-KING-
LIFESTYLE 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MR-KiNG | Lifestyle</title>
    <style>
        /* Paleta de colores */
        :root {
            --rojo-vermillon: #E34234;
            --negro: #000000;
            --blanco: #FFFFFF;
            --gris-topo: #504A4B;
        }

        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--negro);
            color: var(--blanco);
        }

        /* Encabezado principal (Hero) */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: var(--negro);
            flex-direction: column;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            color: var(--rojo-vermillon);
        }

        .btn-completar {
            background-color: var(--rojo-vermillon);
            color: var(--blanco);
            border: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: 0.3s ease;
            margin-top: 20px;
        }

        .btn-completar:hover {
            background-color: var(--gris-topo);
        }

        /* Formulario de Contrato */
        .formulario {
            background-color: var(--gris-topo);
            padding: 30px;
            border-radius: 10px;
            width: 80%;
            max-width: 600px;
            margin: 30px auto;
        }

        .formulario input,
        .formulario select,
        .formulario textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
        }

        .formulario button {
            background-color: var(--rojo-vermillon);
            color: var(--blanco);
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        /* Estilos para el modo oscuro */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: var(--negro);
                color: var(--blanco);
            }
            .hero h1 {
                color: var(--rojo-vermillon);
            }
            .formulario {
                background-color: var(--gris-topo);
            }
            .btn-completar:hover {
                background-color: var(--rojo-vermillon);
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <div class="hero">
        <h1>CONTRATO DE VENTA EN CUOTAS — Plan de pagos seguro y verificado</h1>
        <button class="btn-completar" onclick="window.location.href='#formulario'">Completar Contrato</button>
    </div>

    <!-- Formulario de Contrato -->
    <div class="formulario" id="formulario">
        <h2>Detalles del Contrato</h2>
        <form action="#">
            <label for="nombre">Nombre completo</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="dni">DNI</label>
            <input type="text" id="dni" name="dni" required>

            <label for="telefono">Teléfono</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="producto">Producto</label>
            <input type="text" id="producto" name="producto" required>

            <label for="estado">Estado del producto</label>
            <select id="estado" name="estado">
                <option value="nuevo">Nuevo</option>
                <option value="usado">Usado</option>
            </select>

            <label for="cuotas">Cantidad de cuotas</label>
            <select id="cuotas" name="cuotas">
                <option value="3">3 cuotas</option>
                <option value="6">6 cuotas</option>
                <option value="12">12 cuotas</option>
            </select>

            <label for="forma_pago">Forma de pago</label>
            <select id="forma_pago" name="forma_pago">
                <option value="efectivo">Efectivo</option>
                <option value="transferencia">Transferencia</option>
            </select>

            <button type="submit">Generar Contrato</button>
        </form>
    </div>

</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MR-KiNG | Lifestyle</title>
    <style>
        /* Paleta de colores */
        :root {
            --rojo-vermillon: #E34234;
            --negro: #000000;
            --blanco: #FFFFFF;
            --gris-topo: #504A4B;
        }

        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--negro);
            color: var(--blanco);
        }

        /* Encabezado principal (Hero) */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: var(--negro);
            flex-direction: column;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            color: var(--rojo-vermillon);
        }

        .btn-completar {
            background-color: var(--rojo-vermillon);
            color: var(--blanco);
            border: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: 0.3s ease;
            margin-top: 20px;
        }

        .btn-completar:hover {
            background-color: var(--gris-topo);
        }

        /* Formulario de Contrato */
        .formulario {
            background-color: var(--gris-topo);
            padding: 30px;
            border-radius: 10px;
            width: 80%;
            max-width: 600px;
            margin: 30px auto;
        }

        .formulario input,
        .formulario select,
        .formulario textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
        }

        .formulario button {
            background-color: var(--rojo-vermillon);
            color: var(--blanco);
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        /* Estilos para el modo oscuro */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: var(--negro);
                color: var(--blanco);
            }
            .hero h1 {
                color: var(--rojo-vermillon);
            }
            .formulario {
                background-color: var(--gris-topo);
            }
            .btn-completar:hover {
                background-color: var(--rojo-vermillon);
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <div class="hero">
        <h1>CONTRATO DE VENTA EN CUOTAS — Plan de pagos seguro y verificado</h1>
        <button class="btn-completar" onclick="window.location.href='#formulario'">Completar Contrato</button>
    </div>

    <!-- Formulario de Contrato -->
    <div class="formulario" id="formulario">
        <h2>Detalles del Contrato</h2>
        <form action="#">
            <label for="nombre">Nombre completo</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="dni">DNI</label>
            <input type="text" id="dni" name="dni" required>

            <label for="telefono">Teléfono</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="producto">Producto</label>
            <input type="text" id="producto" name="producto" required>

            <label for="estado">Estado del producto</label>
            <select id="estado" name="estado">
                <option value="nuevo">Nuevo</option>
                <option value="usado">Usado</option>
            </select>

            <label for="cuotas">Cantidad de cuotas</label>
            <select id="cuotas" name="cuotas">
                <option value="3">3 cuotas</option>
                <option value="6">6 cuotas</option>
                <option value="12">12 cuotas</option>
            </select>

            <label for="forma_pago">Forma de pago</label>
            <select id="forma_pago" name="forma_pago">
                <option value="efectivo">Efectivo</option>
                <option value="transferencia">Transferencia</option>
            </select>

            <button type="submit">Generar Contrato</button>
        </form>
    </div>

</body>
</html>
