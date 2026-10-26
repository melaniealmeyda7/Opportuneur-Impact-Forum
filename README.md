# OPPORTUNEUR IMPACT FORUM 2026 — PORTAL DE PANELISTAS 🎙️
> **Portal VIP y Dashboard Privado para Ponentes y Moderadores**  
> **Subdominio Oficial:** [speakers.polyglotmap.com](https://speakers.polyglotmap.com)  
> **Repositorio Oficial:** [melaniealmeyda7/Opportuneur-Impact-Forum](https://github.com/melaniealmeyda7/Opportuneur-Impact-Forum)

---

## 🌐 Configuración DNS en Namecheap para Vercel (`speakers.polyglotmap.com`)

Para vincular este repositorio en Vercel y asociarlo con el subdominio en Namecheap:

### 1. En Vercel:
1. Conecta el repositorio `melaniealmeyda7/Opportuneur-Impact-Forum`.
2. Ve a **Project Settings** > **Domains**.
3. Añade: `speakers.polyglotmap.com`.

### 2. En Namecheap (Advanced DNS):
1. Inicia sesión en **Namecheap** > **Domain List** > Haz clic en **Manage** al lado de `polyglotmap.com`.
2. Ve a la pestaña **Advanced DNS**.
3. En la sección **Host Records**, haz clic en **Add New Record**:

| Tipo de Registro | Host | Valor / Target | TTL |
| :--- | :--- | :--- | :--- |
| **CNAME Record** | `speakers` | `cname.vercel-dns.com.` | `Automatic` (o `1 min`) |

*(Nota: Si Vercel solicita verificación de propiedad mediante TXT)*:

| Tipo de Registro | Host | Valor / Target | TTL |
| :--- | :--- | :--- | :--- |
| **TXT Record** | `_vercel` *(o el proporcionado por Vercel)* | `vc-domain-verify=speakers.polyglotmap.com,...` | `Automatic` |

---

## 🔑 Credenciales de Acceso

### Moderación General (Acceso Total & Directorio)
- **Melanie Almeyda**: Usuario: `admin.melanie` | Clave: `Admin#Melanie2026`
- **Nataly Napanga**: Usuario: `admin.nataly` | Clave: `Admin#Nataly2026`

### Panelistas Oficiales (Aislamiento Total — Cada uno ve su panel y preguntas)
1. **Cristian Gutiérrez** (Área 1): `cristian.gutierrez` | `Opp2026!Cristian`
2. **María Gracia Agurto** (Área 1): `mariagracia.agurto` | `Opp2026!MariaGracia`
3. **Alfonso Rangel** (Área 1): `alfonso.rangel` | `Opp2026!Alfonso`
4. **Elizabeth Javier** (Área 2): `elizabeth.javier` | `Opp2026!Elizabeth`
5. **Natalia Bejar** (Área 2): `natalia.bejar` | `Opp2026!Natalia`
6. **Rosa Centurión** (Área 2): `rosa.centurion` | `Opp2026!Rosa`
7. **Luis Avelán** (Área 3): `luis.avellan` | `Opp2026!Luis`
8. **Jorge Escalante** (Área 3): `jorge.escalante` | `Opp2026!Jorge`
9. **Roberto Romero** (Área 3): `roberto.romero` | `Opp2026!Roberto`
10. **José Mendoza** (Área 4): `jose.mendoza` | `Opp2026!Jose`
11. **Andrea Vivas** (Área 4): `andrea.vivas` | `Opp2026!Andrea`
12. **Gabriela Gaitán** (Área 4): `gabriela.gaitan` | `Opp2026!Gabriela`
