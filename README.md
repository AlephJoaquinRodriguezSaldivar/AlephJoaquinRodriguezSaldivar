# Proyecto
Mi primer proyecto.

Autor: Aleph Rodriguez
Fecha: 25 de octubre.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseñador Freelancer</title>
    <link rel="preload" href="css/styles.css" as="style"> 
    <link href="css/styles.css" rel="stylesheet">
</head>

<body>
    <header>
        <h1>Aleph Rodriguez <span>Freelancer</span></h1>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Sobre Nostros</a>
        <a href="#">Clientes</a>
        <a href="#">Contacto</a>
    </nav>

    
    <section>
        <h1>Perritos en busca de un nuevo hogar</h1>

        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin" width="60" height="60" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ff4500" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
            <circle cx="12" cy="11" r="3" />
            <path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
         </svg>
        
        <p>Ciudad de México</p>

        <a href="#">Contactar</a>
    </section>
  
    <main>
        <h2>Nuestros Servicios</h2>

        <section>
            <h3>Entrenadores</h3>
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-user-check" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                <circle cx="9" cy="7" r="4" />
                <path d="M3 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" />
                <path d="M16 11l2 2l4 -4" />
              </svg>
            <p> Quisque lacinia porttitor nisl ac accumsan. Cras vel hendrerit nunc. Integer ultricies felis id risus accumsan,
            vitae vulputate tortor egestas.</p>
        </section>

        <section>
            <h3>Venta de alimento</h3>
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-grain" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                <circle cx="4.5" cy="9.5" r="1" />
                <circle cx="9.5" cy="4.5" r="1" />
                <circle cx="9.5" cy="14.5" r="1" />
                <circle cx="4.5" cy="19.5" r="1" />
                <circle cx="14.5" cy="9.5" r="1" />
                <circle cx="19.5" cy="4.5" r="1" />
                <circle cx="14.5" cy="19.5" r="1" />
                <circle cx="19.5" cy="14.5" r="1" />
              </svg>
            <p> Quisque lacinia porttitor nisl ac accumsan. Cras vel hendrerit nunc. Integer ultricies felis id risus accumsan,
            vitae vulputate tortor egestas.</p>
        </section>

        <section>
            <h3>Adopción</h3>
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-home" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                <polyline points="5 12 3 12 12 3 21 12 19 12" />
                <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />
                <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" />
              </svg>                           
            <p> Quisque lacinia porttitor nisl ac accumsan. Cras vel hendrerit nunc. Integer ultricies felis id risus accumsan,
            vitae vulputate tortor egestas.</p>
        </section>
    </main>

    <section>
        <h2>Contacto</h2>

        <form>
            <fieldset>
                <legend>Contactanos llenado todos los campos</legend>

                <div>
                    <label>Nombre</label>
                    <input type="text" placeholder="Tu Nombre">
                </div>

                <div>
                    <label>Teléfono</label>
                    <input type="tel" placeholder="Tu Teléfono">
                </div>

                <div>
                    <label>Correo</label>
                    <input type="email" placeholder="Tu email">
                </div>

                <div>
                    <label>Mansaje</label>
                    <textarea></textarea>
                </div>

                <div>
                    <input type="submit" value="Enviar">
                </div>
                

            </fieldset>
        </form>
    </section>
    
    <footer>
        <p>Todos los derechos reservados, Aleph Rodriguez</p>
    </footer>

</body>

</html>
