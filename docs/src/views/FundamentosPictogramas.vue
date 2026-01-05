<script setup>
import EjemploCodigo from '../componetes/EjemploCodigo.vue'
</script>
<template>
  <div class="contenedor m-y-maximo">

    <div class="ancho-lectura">
      <h1>Pictogramas</h1>
      <p>
        La mayoría de los pictogramas utilizados en Sisdai se recuperaron de
        <a href="https://carbondesignsystem.com" target="_blank" ref="noopener noreferrer">Carbon Design System</a>, 
        sistema de código abierto.
      </p>
      <p>
        Además, hemos incorporado pictogramas específicos que cumplen con 
        requisitos de comunicación particulares, siguiendo la plantilla 
        maestra del sistema. Estos pictogramas se han adaptado para funcionar 
        como parte de la tipografía, aumentando así su flexibilidad de uso 
        en sitios web. Se implementan a través de clases aplicadas a etiquetas 
        de texto, tal como se ilustra en el siguiente ejemplo: 
      </p>

      <EjemploCodigo
      tipo='HTML'
      codigo='
        <h2 class="pictograma-actualizar"></h2>
      '
      />
    </div>
    
    <details class="m-y-3">
      <summary>Listado de clases de pictograma</summary>
      <div class="columns-3 columns-1-mov">
        <div>
          <span class="pictograma-actualizar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-actualizar</span>
        </div>
        <div>
          <span class="pictograma-adelantar-10"></span>
          <span class="pictograma-clase-ejemplo">pictograma-adelantar-10</span>
        </div>
        <div>
          <span class="pictograma-agregar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-agregar</span>
        </div>
        <div>
          <span class="pictograma-alerta"></span>
          <span class="pictograma-clase-ejemplo">pictograma-alerta</span>
        </div>
        <div>
          <span class="pictograma-angulo-abajo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-abajo</span>
        </div>
        <div>
          <span class="pictograma-angulo-arriba"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-arriba</span>
        </div>
        <div>
          <span class="pictograma-angulo-derecho"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-derecho</span>
        </div>
        <div>
          <span class="pictograma-angulo-doble-abajo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-doble-abajo</span>
        </div>
        <div>
          <span class="pictograma-angulo-doble-arriba"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-doble-arriba</span>
        </div>
        <div>
          <span class="pictograma-angulo-doble-derecha"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-doble-derecha</span>
        </div>
        <div>
          <span class="pictograma-angulo-doble-izquierda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-doble-izquierda</span>
        </div>
        <div>
          <span class="pictograma-angulo-izquierdo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-angulo-izquierdo</span>
        </div>
        <div>
          <span class="pictograma-aprobado"></span>
          <span class="pictograma-clase-ejemplo">pictograma-aprobado</span>
        </div>
        <div>
          <span class="pictograma-archivo-descargar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-archivo-descargar</span>
        </div>
        <div>
          <span class="pictograma-archivo-subir"></span>
          <span class="pictograma-clase-ejemplo">pictograma-archivo-subir</span>
        </div>
        <div>
          <span class="pictograma-arrastrar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-arrastrar</span>
        </div>
        <div>
          <span class="pictograma-ayuda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ayuda</span>
        </div>
        <div>
          <span class="pictograma-bajar-capa"></span>
          <span class="pictograma-clase-ejemplo">pictograma-bajar-capa</span>
        </div>
        <div>
          <span class="pictograma-bot"></span>
          <span class="pictograma-clase-ejemplo">pictograma-bot</span>
        </div>
        <div>
          <span class="pictograma-buscar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-buscar</span>
        </div>
        <div>
          <span class="pictograma-calendario"></span>
          <span class="pictograma-clase-ejemplo">pictograma-calendario</span>
        </div>
        <div>
          <span class="pictograma-cambio-tipografia"></span>
          <span class="pictograma-clase-ejemplo">pictograma-cambio-tipografia</span>
        </div>
        <div>
          <span class="pictograma-capa-lineas"></span>
          <span class="pictograma-clase-ejemplo">pictograma-capa-lineas</span>
        </div>
        <div>
          <span class="pictograma-capa-poligono"></span>
          <span class="pictograma-clase-ejemplo">pictograma-capa-poligono</span>
        </div>
        <div>
          <span class="pictograma-capa-puntos"></span>
          <span class="pictograma-clase-ejemplo">pictograma-capa-puntos</span>
        </div>
        <div>
          <span class="pictograma-capas"></span>
          <span class="pictograma-clase-ejemplo">pictograma-capas</span>
        </div>
        <div>
          <span class="pictograma-casilla"></span>
          <span class="pictograma-clase-ejemplo">pictograma-casilla</span>
        </div>
        <div>
          <span class="pictograma-casilla-verificada"></span>
          <span class="pictograma-clase-ejemplo">pictograma-casilla-verificada</span>
        </div>
        <div>
          <span class="pictograma-cerrar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-cerrar</span>
        </div>
        <div>        
          <span class="pictograma-cerrar-sesion"></span>
          <span class="pictograma-clase-ejemplo">pictograma-cerrar-sesion</span>
        </div>
        <div>        
          <span class="pictograma-chat"></span>
          <span class="pictograma-clase-ejemplo">pictograma-chat</span>
        </div>
        <div>
          <span class="pictograma-colaborar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-colaborar</span>
        </div>
        <div>
          <span class="pictograma-compartir"></span>
          <span class="pictograma-clase-ejemplo">pictograma-compartir</span>
        </div>
        <div>
          <span class="pictograma-contraste"></span>
          <span class="pictograma-clase-ejemplo">pictograma-contraste</span>
        </div>
        <div>
          <span class="pictograma-control-comenzar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-control-comenzar</span>
        </div>
        <div>
          <span class="pictograma-control-detener"></span>
          <span class="pictograma-clase-ejemplo">pictograma-control-detener</span>
        </div>
        <div>
          <span class="pictograma-control-final"></span>
          <span class="pictograma-clase-ejemplo">pictograma-control-final</span>
        </div>
        <div>
          <span class="pictograma-control-inicio"></span>
          <span class="pictograma-clase-ejemplo">pictograma-control-inicio</span>
        </div>
        <div>
          <span class="pictograma-control-pausa"></span>
          <span class="pictograma-clase-ejemplo">pictograma-control-pausa</span>
        </div>
        <div>
          <span class="pictograma-copiar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-copiar</span>
        </div>
        <div>
          <span class="pictograma-documento"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento</span>
        </div>
        <div>
          <span class="pictograma-documento-csv"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-csv</span>
        </div>
        <div>
          <span class="pictograma-documento-geojson"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-geojson</span>
        </div>
        <div>
          <span class="pictograma-documento-geopaquete"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-geopaquete</span>
        </div>
        <div>
          <span class="pictograma-documento-pdf"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-pdf</span>
        </div>
        <div>
          <span class="pictograma-documento-png"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-png</span>
        </div>
        <div>
          <span class="pictograma-documento-ppt"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-ppt</span>
        </div>
        <div>
          <span class="pictograma-documento-word"></span>
          <span class="pictograma-clase-ejemplo">pictograma-documento-word</span>
        </div>
        <div>
          <span class="pictograma-editar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-editar</span>
        </div>
        <div>
          <span class="pictograma-eliminar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-eliminar</span>
        </div>
        <div>
          <span class="pictograma-enlace-subrayado"></span>
          <span class="pictograma-clase-ejemplo">pictograma-enlace-subrayado</span>
        </div>
        <div>
          <span class="pictograma-escribir"></span>
          <span class="pictograma-clase-ejemplo">pictograma-escribir</span>
        </div>
        <div>
          <span class="pictograma-estrella"></span>
          <span class="pictograma-clase-ejemplo">pictograma-estrella</span>
        </div>
        <div>
          <span class="pictograma-explorar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-explorar</span>
        </div>
        <div>
          <span class="pictograma-filtro"></span>
          <span class="pictograma-clase-ejemplo">pictograma-filtro</span>
        </div>
        <div>
          <span class="pictograma-flecha-abajo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-abajo</span>
        </div>
        <div>
          <span class="pictograma-flecha-abajo-derecha"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-abajo-derecha</span>
        </div>
        <div>
          <span class="pictograma-flecha-abajo-izquierda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-abajo-izquierda</span>
        </div>
        <div>
          <span class="pictograma-flecha-arriba"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-arriba</span>
        </div>
        <div>
          <span class="pictograma-flecha-arriba-derecha"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-arriba-derecha</span>
        </div>
        <div>
          <span class="pictograma-flecha-arriba-izquierda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-arriba-izquierda</span>
        </div>
        <div>
          <span class="pictograma-flecha-derecha"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-derecha</span>
        </div>
        <div>
          <span class="pictograma-flecha-izquierda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-izquierda</span>
        </div>
        <div>
          <span class="pictograma-flechas-horizontales"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flechas-horizontales</span>
        </div>
        <div>
          <span class="pictograma-flkt"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flkt</span>
        </div>
        <div>
          <span class="pictograma-grupo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-grupo</span>
        </div>
        <div>
          <span class="pictograma-guardar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-guardar</span>
        </div>
        <div>
          <span class="pictograma-social-facebook"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-facebook</span>
        </div>
        <div>
          <span class="pictograma-social-github"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-github</span>
        </div>
        <div>
          <span class="pictograma-social-instagram"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-instagram</span>
        </div>
        <div>
          <span class="pictograma-social-linkedin"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-linkedin</span>
        </div>
        <div>
          <span class="pictograma-social-twitter"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-twitter</span>
        </div>
        <div>
          <span class="pictograma-social-youtube"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-youtube</span>
        </div>
        <div>
          <span class="pictograma-social-x"></span>
          <span class="pictograma-clase-ejemplo">pictograma-social-x</span>
        </div>
        <div>
          <span class="pictograma-subir-capa"></span>
          <span class="pictograma-clase-ejemplo">pictograma-subir-capa</span>
        </div>
        <div>
          <span class="pictograma-ia"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ia</span>
        </div>
        <div>
          <span class="pictograma-informacion"></span>
          <span class="pictograma-clase-ejemplo">pictograma-informacion</span>
        </div>
        <div>
          <span class="pictograma-inicio"></span>
          <span class="pictograma-clase-ejemplo">pictograma-inicio</span>
        </div>
        <div>
          <span class="pictograma-limpiar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-limpiar</span>
        </div>
        <div>
          <span class="pictograma-localizacion"></span>
          <span class="pictograma-clase-ejemplo">pictograma-localizacion</span>
        </div>
        <div>
          <span class="pictograma-mapa-centro"></span>
          <span class="pictograma-clase-ejemplo">pictograma-mapa-centro</span>
        </div>
        <div>
          <span class="pictograma-mapa-generador"></span>
          <span class="pictograma-clase-ejemplo">pictograma-mapa-generador</span>
        </div>
        <div>
          <span class="pictograma-maximizar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-maximizar</span>
        </div>
        <div>
          <span class="pictograma-menu"></span>
          <span class="pictograma-clase-ejemplo">pictograma-menu</span>
        </div>
        <div>
          <span class="pictograma-mexico"></span>
          <span class="pictograma-clase-ejemplo">pictograma-mexico</span>
        </div>
        <div>
          <span class="pictograma-minimizar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-minimizar</span>
        </div>
        <div>
          <span class="pictograma-mover"></span>
          <span class="pictograma-clase-ejemplo">pictograma-mover</span>
        </div>
        <div>
          <span class="pictograma-nivel"></span>
          <span class="pictograma-clase-ejemplo">pictograma-nivel</span>
        </div>
        <div>
          <span class="pictograma-norte"></span>
          <span class="pictograma-clase-ejemplo">pictograma-norte</span>
        </div>
        <div>
          <span class="pictograma-numerales"></span>
          <span class="pictograma-clase-ejemplo">pictograma-numerales</span>
        </div>
        <div>
          <span class="pictograma-ojo-ocultar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ojo-ocultar</span>
        </div>
        <div>
          <span class="pictograma-ojo-ver"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ojo-ver</span>
        </div>
        <div>
          <span class="pictograma-ordenar-alfabetico-asc"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ordenar-alfabetico-asc</span>
        </div>
        <div>
          <span class="pictograma-ordenar-alfabetico-desc"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ordenar-alfabetico-desc</span>
        </div>
        <div>
          <span class="pictograma-ordenar-asc"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ordenar-asc</span>
        </div>
        <div>
          <span class="pictograma-ordenar-desc"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ordenar-desc</span>
        </div>
        <div>
          <span class="pictograma-persona"></span>
          <span class="pictograma-clase-ejemplo">pictograma-persona</span>
        </div>
        <div>
          <span class="pictograma-previsualizar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-previsualizar</span>
        </div>
        <div>
          <span class="pictograma-privado"></span>
          <span class="pictograma-clase-ejemplo">pictograma-privado</span>
        </div>
        <div>
          <span class="pictograma-proyectos"></span>
          <span class="pictograma-clase-ejemplo">pictograma-proyectos</span>
        </div>
        <div>
          <span class="pictograma-regresar-10"></span>
          <span class="pictograma-clase-ejemplo">pictograma-regresar-10</span>
        </div>
        <div>
          <span class="pictograma-reporte"></span>
          <span class="pictograma-clase-ejemplo">pictograma-reporte</span>
        </div>
        <div>
          <span class="pictograma-reloj"></span>
          <span class="pictograma-clase-ejemplo">pictograma-reloj</span>
        </div>
        <div>
          <span class="pictograma-restar"></span>
          <span class="pictograma-clase-ejemplo">pictograma-restar</span>
        </div>
        <div>
          <span class="pictograma-tabla"></span>
          <span class="pictograma-clase-ejemplo">pictograma-tabla</span>
        </div>
        <div>
          <span class="pictograma-teclado"></span>
          <span class="pictograma-clase-ejemplo">pictograma-teclado</span>
        </div>
        <div>
          <span class="pictograma-ubicacion"></span>
          <span class="pictograma-clase-ejemplo">pictograma-ubicacion</span>
        </div>
        <div>
          <span class="pictograma-vista-simplificada"></span>
          <span class="pictograma-clase-ejemplo">pictograma-vista-simplificada</span>
        </div>
        <div>
          <span class="pictograma-voto-no"></span>
          <span class="pictograma-clase-ejemplo">pictograma-voto-no</span>
        </div>
        <div>
          <span class="pictograma-voto-si"></span>
          <span class="pictograma-clase-ejemplo">pictograma-voto-si</span>
        </div>
        <div>
          <span class="pictograma-accesibilidad"></span>
          <span class="pictograma-clase-ejemplo">pictograma-accesibilidad</span>
        </div>
        <div>
          <span class="pictograma-restablecer"></span>
          <span class="pictograma-clase-ejemplo">pictograma-restablecer</span>
        </div>
        <div>
          <span class="pictograma-flecha-izquierda"></span>
          <span class="pictograma-clase-ejemplo">pictograma-flecha-izquierda</span>
        </div>
        <div>
          <span class="pictograma-enlace-externo"></span>
          <span class="pictograma-clase-ejemplo">pictograma-enlace-externo</span>
        </div>
        <div>
          <span class="pictograma-metadatos"></span>
          <span class="pictograma-clase-ejemplo">pictograma-metadatos</span>
        </div>
        <div>
          <span class="pictograma-visualizador"></span>
          <span class="pictograma-clase-ejemplo">pictograma-visualizador</span>
        </div>
        <div>
          <span class="pictograma-zoom-instruccional"></span>
          <span class="pictograma-clase-ejemplo">pictograma-zoom-instruccional</span>
        </div>
      </div>
    </details>

    <details class="m-y-3" open>
      <summary>Tipografía Sisdai</summary>
      <div class="columns-3 columns-1-mov">
        <div>
          <span class="pic-sisdai-accesibilidad"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-accesibilidad</span>
        </div>
        <div>
          <span class="pic-sisdai-actualizar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-actualizar</span>
        </div>
        <div>
          <span class="pic-sisdai-adelantar-10"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-adelantar-10</span>
        </div>
        <div>
          <span class="pic-sisdai-agregar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-agregar</span>
        </div>
        <div>
          <span class="pic-sisdai-alerta"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-alerta</span>
        </div>
        <div>
          <span class="pic-sisdai-aprobado"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-aprobado</span>
        </div>
        <div>
          <span class="pic-sisdai-descargar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-descargar</span>
        </div>
        <div>
          <span class="pic-sisdai-subir-archivo"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-subir-archivo</span>
        </div>
        <div>
          <span class="pic-sisdai-arrastrar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-arrastrar</span>
        </div>
        <div>
          <span class="pic-sisdai-ayuda"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-ayuda</span>
        </div>
        <div>
          <span class="pic-sisdai-bajar-capa"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-bajar-capa</span>
        </div>
        <div>
          <span class="pic-sisdai-buscar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-buscar</span>
        </div>
        <div>
          <span class="pic-sisdai-calendario"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-calendario</span>
        </div>
        <div>
          <span class="pic-sisdai-cambiar-tipografia"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-cambiar-tipografia</span>
        </div>
        <div>
          <span class="pic-sisdai-capa-puntos"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-capa-puntos</span>
        </div>
        <div>
          <span class="pic-sisdai-capas"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-capas</span>
        </div>
        <div>
          <span class="pic-sisdai-casilla-verificada"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-casilla-verificada</span>
        </div>
        <div>
          <span class="pic-sisdai-casilla"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-casilla</span>
        </div>
        <div>
          <span class="pic-sisdai-cerrar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-cerrar</span>
        </div>
        <div>
          <span class="pic-sisdai-colaborar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-colaborar</span>
        </div>
        <div>
          <span class="pic-sisdai-compartir"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-compartir</span>
        </div>
        <div>
          <span class="pic-sisdai-contraste"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-contraste</span>
        </div>
        <div>
          <span class="pic-sisdai-control-comenzar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-comenzar</span>
        </div>
        <div>
          <span class="pic-sisdai-control-detener"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-detener</span>
        </div>
        <div>
          <span class="pic-sisdai-control-final"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-final</span>
        </div>
        <div>
          <span class="pic-sisdai-control-final"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-final</span>
        </div>
        <div>
          <span class="pic-sisdai-control-inicio"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-inicio</span>
        </div>
        <div>
          <span class="pic-sisdai-control-pausa"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-control-pausa</span>
        </div>
        <div>
          <span class="pic-sisdai-copiar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-copiar</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-csv"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-csv</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-geojson"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-geojson</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-geopaquete"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-geopaquete</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-pdf"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-pdf</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-png"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-png</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-ppt"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-ppt</span>
        </div>
        <div>
          <span class="pic-sisdai-documento-word"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento-word</span>
        </div>
        <div>
          <span class="pic-sisdai-documento"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-documento</span>
        </div>
        <div>
          <span class="pic-sisdai-editar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-editar</span>
        </div>
        <div>
          <span class="pic-sisdai-eliminar"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-eliminar</span>
        </div>
        <div>
          <span class="pic-sisdai-enlace-externo"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-enlace-externo</span>
        </div>
        <div>
          <span class="pic-sisdai-enlace-subrayado"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-enlace-subrayado</span>
        </div>
        <div>
          <span class="pic-sisdai-error"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-error</span>
        </div>
        <div>
          <span class="pic-sisdai-flkt"></span>
          <span class="pictograma-clase-ejemplo">pic-sisdai-flkt</span>
        </div>
      </div>
    </details>

    <details class="m-y-3" open>
      <summary>Tipografia Delitos</summary>
      <div class="columns-3 columns-1-mov">
        <div>
          <span class="pic-delito-a"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-a</span>
        </div>
        <div>
          <span class="pic-delito-b"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-b</span>
        </div>
        <div>
          <span class="pic-delito-c"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-c</span>
        </div>
        <div>
          <span class="pic-delito-d"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-d</span>
        </div>
        <div>
          <span class="pic-delito-f"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-f</span>
        </div>
        <div>
          <span class="pic-delito-g"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-g</span>
        </div>
        <div>
          <span class="pic-delito-h"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-h</span>
        </div>
        <div>
          <span class="pic-delito-i"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-i</span>
        </div>
        <div>
          <span class="pic-delito-j"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-j</span>
        </div>
        <div>
          <span class="pic-delito-k"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-k</span>
        </div>
        <div>
          <span class="pic-delito-l"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-l</span>
        </div>
        <div>
          <span class="pic-delito-m"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-m</span>
        </div>
        <div>
          <span class="pic-delito-n"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-n</span>
        </div>
        <div>
          <span class="pic-delito-o"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-o</span>
        </div>
        <div>
          <span class="pic-delito-p"></span>
          <span class="pictograma-clase-ejemplo">pic-delito-p</span>
        </div>
      </div>
    </details>
    

    <div class="contenedor ancho-lectura">
      <h2 class="m-t-10">Tamaños especiales</h2>
      <p>
        Al integrarse con la tipografía, el tamaño de los pictogramas varía dependiendo 
        de la etiqueta en la que se encuentren. Sin embargo,  el Sisdai específica el 
        uso de los tamaños originales o aquellos que correspondan a incrementos de 24px, 
        32px y 48px. Para esto, se han creado las clases <code>.pictograma-chico</code>, 
        <code>.pictograma-mediano</code> y <code>.pictograma-grande</code>.
      </p>
      <EjemploCodigo
      tipo='HTML'
      codigo='
        <span class="pictograma-flkt pictograma-chico"></span>
        <span class="pictograma-flkt pictograma-mediano"></span>
        <span class="pictograma-flkt pictograma-grande"></span>
      '
      />

      <h3 class="m-t-10">Tamaños especiales responsivos</h3>
      <p>
        Al igual que con otras clases responsivas, los pictogramas adaptan su tamaño 
        agregando el sufijo <code>-mov</code> para dispositivos móviles y <code>-esc</code> 
        para dispositivos de escritorio.
      </p>
      <EjemploCodigo
      tipo='HTML'
      codigo='
        <span class="pictograma-flkt pictograma-chico-mov pictograma-grande-esc"></span>
      '
      />
    </div>

  </div>
</template>
