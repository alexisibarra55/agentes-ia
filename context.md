# Proyecto: Landing Pages para Servicios de Agentes IA

## Descripción
Landing pages para captar clientes interesados en agentes IA personalizados. El servicio consiste en crear asistentes virtuales expertos que trabajan 24/7 para el cliente.

## Stack
- HTML/CSS puro (sin frameworks)
- Diseño Glassmorphism
- Formspree para formularios (ID: mnnebojg)
- GitHub Pages para hosting
- Repo: https://github.com/alexisibarra55/agentes-ia

## Archivos principales
- `index.html`: Landing principal (estilo glassmorphism)
- `gracias.html`: Página de agradecimiento post-formulario

## Estilo visual actual (Glassmorphism)
- Fondo: Gradiente púrpura/rosa (#1e1b4b → #701a75)
- Efecto glass: backdrop-filter blur(20px)
- Orbes flotantes animados con blur
- Tipografía: Plus Jakarta Sans (Google Fonts)
- Acentos: Púrpura (#a855f7) y Rosa (#ec4899)
- Bordes: rgba(255, 255, 255, 0.2)
- Inputs: Fondo semi-transparente con focus púrpura

## Otras versiones disponibles
1. **Synthwave**: Neón retro, grilla animada, colores cyan/rosa
2. **Minimalista**: Grises + azul corporativo, limpio, elegante
3. **Dark Mode**: Estilo Vercel/GitHub, fondo negro, acento verde

## Copy principal
- **Título**: "Todos van a tener uno. Vos también deberías ✦"
- **Subtítulo**: "La IA no es el futuro, es el presente. Empresas y profesionales ya están usando agentes para trabajar menos y lograr más. La pregunta no es si vas a usarlo, es cuándo."
- **Testimonial footer**: "Uso agentes IA en mi trabajo y vida diaria. Me cambiaron la forma de trabajar. Vos también deberías probarlo."

## Formulario (12 campos)
### Sección: Sobre vos
- Nombre completo (required)
- Email de contacto (required)
- Empresa o proyecto (opcional)
- ¿A qué te dedicás? (required)

### Sección: Tu asistente ideal
- ¿Qué rol querés que cumpla? (required)
- ¿Qué problema te resuelve? (required)
- Tareas que debería hacer (required)
- ¿Algo que NO debería hacer? (opcional)
- ¿Cómo querés que se comunique? (select: formal-técnico, formal-amigable, informal-profesional, casual-cercano)

### Sección: Detalles finales
- ¿Necesita conocer info específica tuya? (select)
- ¿Para cuándo lo necesitás? (select: asap, 1-2 semanas, ~1 mes, sin urgencia)
- ¿Algo más que quieras contarme? (opcional)

## Configuración Formspree
- Form ID: mnnebojg
- Redirect después de envío: gracias.html
- Campo oculto: `_next` con URL de thank you page

## Datos de contacto
- Email: alexx.ibarra@gmail.com
- GitHub: alexisibarra55

## URL en producción
https://alexisibarra55.github.io/agentes-ia/

## Notas de diseño
- Los section headers tienen fondo púrpura semi-transparente con borde izquierdo
- Scrollbar personalizado en textareas (fino, color púrpura)
- Botón submit con gradiente y efecto hover con glow
- Cards de beneficios con efecto glass y hover lift
- Mobile responsive (breakpoint 640px)

## Próximas mejoras pendientes
- [ ] Verificar que el email se muestre correctamente en el footer
- [ ] Testear thank you page redirect
- [ ] Considerar agregar más versiones de landing para A/B testing
