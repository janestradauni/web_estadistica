🚗 3 Mapas Geodescriptivos — Sector Automóvil Eléctrico
Mapa 1 — Índice EPA animado por mes (univariante)
Variables: air_quality_us.epa.index, latitude, longitude, last_updated
Tipo: GIF animado — color del punto = categoría EPA (verde→rojo)

¿Por qué este gráfico?
El índice EPA es el resumen oficial de la calidad del aire que usan los gobiernos para tomar decisiones regulatorias. Cuando una ciudad supera categoría 3 de forma recurrente, las autoridades están obligadas a actuar con restricciones de tráfico (ZBE, peajes de contaminación, prohibiciones). Ver su evolución mes a mes permite al inversor identificar qué ciudades están en el umbral de restringir los coches de combustión — exactamente donde un concesionario o red de carga eléctrica tiene más futuro.

Mapa 2 — Bivariante NO₂ vs CO (bivariante)
Variables: air_quality_Nitrogen_dioxide, air_quality_Carbon_Monoxide, latitude, longitude
Tipo: Estático — tamaño burbuja = NO₂, color = CO

¿Por qué este gráfico?
NO₂ y CO son los dos gases producidos exclusivamente por motores de combustión interna — no por industria ni calefacción. Si una ciudad tiene ambos altos simultáneamente, el problema es inequívocamente el tráfico rodado, no otras fuentes. Esto es el argumento más sólido para convencer a un inversor: "esta ciudad tiene un problema de tráfico demostrable con datos, y la solución es el vehículo eléctrico". Un punto grande Y oscuro = oportunidad máxima.

Mapa 3 — Animado PM10 + NO₂ en el tiempo (bivariante) ✅ Ya hecho
Variables: air_quality_PM10, air_quality_Nitrogen_dioxide, latitude, longitude, last_updated
Tipo: GIF — tamaño = PM10, color = NO₂

¿Por qué este gráfico?
Combina partículas (PM10, que generan restricciones) con el gas de tráfico (NO₂) a lo largo del tiempo. Permite ver si el problema es estructural (presente todo el año → mercado seguro para invertir) o estacional (solo en invierno → mercado con demanda concentrada). Esta distinción cambia completamente la estrategia de entrada: en ciudades con problema estructural se invierte en infraestructura permanente; en ciudades estacionales se ajusta el timing de lanzamiento.







SOLAR=


EOLICA=



HIDRAULICA=




☀️ PLACAS SOLARES
1. Mapa animado UV Index por mes (univariante)
Variables: uv_index, latitude, longitude, last_updated

Tipo: GIF — burbuja tamaño+color = UV index

Por qué: Muestra qué ciudades tienen más radiación solar a lo largo del año y en qué meses es óptimo instalar/rentabilizar placas. El inversor ve exactamente cuándo y dónde el sol es más intenso.

2. Mapa estático bivariante: UV vs Nubosidad (bivariante)
Variables: uv_index, cloud, latitude, longitude

Tipo: Scatter geográfico — tamaño = UV, color = % nubosidad

Por qué: Una ciudad puede tener UV alto pero estar siempre nublada (inútil para solar). Este mapa identifica las ciudades con UV alto Y poca nube — el sweetspot real para invertir.

3. Mapa interactivo días sin lluvia (univariante)
Variables: rain, latitude, longitude

Tipo: Plotly interactivo — choropleth/burbujas con hover

Por qué: Los días de lluvia reducen la generación solar. El hover muestra el % de días con lluvia por ciudad, permitiendo comparar de un clic.

💨 EÓLICA
1. Mapa animado velocidad del viento por mes (univariante)
Variables: wind_kph, latitude, longitude, last_updated

Tipo: GIF — tamaño burbuja = velocidad media mensual

Por qué: Igual que con solar, el inversor necesita saber dónde y cuándo sopla más. Se necesita mínimo ~13 km/h para que un aerogenerador sea rentable.

2. Mapa bivariante: Viento vs Visibilidad (bivariante)
Variables: wind_kph, good_visibility, latitude, longitude

Tipo: Estático — tamaño = wind_kph, color = % buena visibilidad

Por qué: La visibilidad baja (niebla, polvo) correlaciona con vientos erráticos. Ciudades con viento fuerte Y buena visibilidad indican flujos de aire estables y predecibles — ideales para parques eólicos.

3. Mapa interactivo dirección + velocidad (bivariante)
Variables: wind_kph, wind_direction, latitude, longitude

Tipo: Plotly interactivo con flechas o rosa de vientos por ciudad (hover)

Por qué: No solo importa cuánto viento hay, sino de dónde viene. El hover muestra la dirección predominante por ciudad para orientar los aerogeneradores correctamente.

💧 HIDRÁULICA
1. Mapa animado lluvia acumulada por mes (univariante)
Variables: rain, latitude, longitude, last_updated

Tipo: GIF — color intensidad = % días con lluvia ese mes

Por qué: Muestra la estacionalidad hídrica. Un río puede estar seco en verano y desbordado en invierno — el inversor necesita saber si hay agua todo el año o solo estacionalmente.

2. Mapa bivariante: Lluvia vs Humedad (bivariante)
Variables: rain, humidity, latitude, longitude

Tipo: Estático — tamaño = % rain, color = humidity media

Por qué: La humedad alta sin lluvia indica agua subterránea o niebla, no apta para hidráulica. La combinación lluvia alta + humedad alta confirma disponibilidad hídrica real y consistente.

3. Mapa interactivo presión atmosférica (univariante)
Variables: pressure_mb, latitude, longitude

Tipo: Plotly interactivo choropleth con hover

Por qué: La presión baja indica frentes lluviosos recurrentes. Ciudades con presión media baja son zonas con más precipitaciones estructurales — mejor para inversión hidráulica a largo plazo.




