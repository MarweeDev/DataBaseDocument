# DataBaseDocument
Repositorio para manejar documentación, queries y diagramas de la base de datos

ejemplo tabla maestra:
m_mod = tabla de modulos

ejemplo tabla predeterminadas - default:
mg_d_use = tabla usuarios

ejemplo tabla general: --MonoGraph
mg_g_pro = tabla proveedores
mg_g_sho = tabla compras
mg_g_ord = tabla ordenes

ejemplo tabla historico o buzon:
mg_h_sho = id, id_producto, cantidad, precio_unit
mg_h_ord = id, id_producto, cantidad, precio_unit

master - m : unica que no necesita cliente

generales - g
default - d
relacionales - r
historicos - h
Errores - l
