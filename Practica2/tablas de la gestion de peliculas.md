Gerarquía de gestión de películas
================================

Descripción:
-----------
* Escenarios asociados con el mantenimiento de las fichas de las películas.

Casos de uso:
-----------
* Comparar películas, Escribir crítica,Añadir imágenes, vídeos, etc de películas,Valorar películas,Listar películas valoradas, Añadir películas,Ver información,Modificar datos de la película, Sugerencias de películas a añadir,Borrar películas.

Actores:
-----------
* Usuario, Sistema, Cliente

Tablas
======

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Comparar Película} & CU-1 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Cliente, Usuario}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario,Opcional}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Tiene que elegir mas de una película}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{ver que película nos parece mejor}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{sirve para ver los datos de varias películas a la vez}                                            \\
\hline
Autor              &              & Fecha   & 9/11/2015     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Escribir crítica} & CU-2 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema, Usuario}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario,Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{El cliente esté registrado}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Las personas den su opinión sobre una película}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es una opinión subjetiva sobre película visualizada}                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015    &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}


\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Añadir imágenes,videos,etc de películas} & CU-3 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario,Optativo}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Que la película esté añadida}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Proporcionar al Usuario información visual sobre la película }                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es añadir los posters, trailer, imágenes de rodaje de una película que esté añadida}                                            \\
\hline
Autor              &              & Fecha   & 9/11/2015     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Valorar Películas} & CU-4 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario,Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{El Usuario esté registrado}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{El Usuario de una puntuación a la película}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es la manera (aparate de las críticas) con la que el usuario puede decir si le ha gustado una película }                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015    &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Lista de películas valoradas} & CU-5 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario,Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{El usuario esté registrado y hya valorado varias películas}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Saber que películas ha valorado el usuario para no repetir}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es un listado de películas que el usuario ha valorado a lo largo de su vida como usuario de la web}                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Añadir Películas} & CU-6 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario,Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Que la película exista o se vaya a estrenar}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Mantener viva la web y actualizarla con películas nuevas}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Consiste en añadir la ficha de una película}                                            \\
\hline
Autor              &              & Fecha    &  9/11/2015   &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Ver información de la película} & CU-7 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario, Cliente}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Que la película exista}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{proporcionar a la persona datos relevantes sobre la película que consulta}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Conjunto de datos sobre una película, guardados en la ficha de esta }                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015    &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Modificar datos de una película} & CU-8 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario. Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{La película que se va a modificar sea la correcta}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{Que los datos sean correctos}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Cambiar información debido a que es errónea o esté incompleta}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es el cambio de información en la ficha de una película}                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015    &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Sugerencias de películas a añadir} & CU-9 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario,Opcional}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Estar registrado en la web}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Ayudar al sistema a añadir fichas sobre películas que no está añadidas}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Es una petición del usuario al Sistema para que este añada ficha de alguna película que no se encuentre en la base de datos}                                            \\
\hline
Autor              &              & Fecha    &  9/11/2015   &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[h]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Borrar Película} & CU-10 \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Haya error en la ficha que deteriore o ocupe memoria}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Eliminar películas repetidas que el sistema haya añadido varias veces}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{Consiste en borrar la ficha de una película}                                            \\
\hline
Autor              &              & Fecha    & 9/11/2015    &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}
