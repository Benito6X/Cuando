CUÁNDO — versión corregida

Cambios:
1. SITE_URL fijo en https://cuando-ten.vercel.app
2. Intro premium de TRÓPIX integrada sin borrar la app.
3. Se eliminaron links demo falsos cuando falla Supabase.
4. Si abres una ruta #plan/#share/#results desde C:/ o localhost, redirige al dominio público.

IMPORTANTE:
- Sube todo a Vercel, incluyendo la carpeta img/.
- Prueba creando un plan desde https://cuando-ten.vercel.app, no desde C:/.
- Los links antiguos demo-xxxxx no se pueden recuperar porque solo existían en sessionStorage de tu PC.
- Si al crear plan aparece error de Supabase, revisa que existan las tablas plans y responses y que las políticas RLS permitan insert/select.
