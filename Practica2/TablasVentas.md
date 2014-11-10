\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Comprar Película} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario(I), Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Las películas para comprar deben estar disponibles para su venta}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{La venta realizada queda almacenada y se le notifica al usuario sobre ello}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Realizar la venta de una película en DVD}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El usuario se conecta a la página web y, una vez que se ha identificado como socio, elige la película y la opción de comprar en DVD (si existe dicha opción y hay unidades disponibles).
Se almacena la venta, el cliente realiza el pago, en ese momento o posteriormente, y se le proporciona un resguardo mediante e-mail.}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Reservar Película} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario(I), Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{Las películas a reservar no están disponibles para su venta en DVD}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{Las películas reservadas se almacenan en una lista ordenada}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Reservar una película y ser informado cuando esté disponible para su venta en DVD}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El usuario se conecta a la página web y, una vez que se ha identificado como socio, elige la película. Al no estar disponible para la compra en DVD, pulsa la opción de reservar, almacenándose el pedido en una lista ordenada.}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Identificar Socio} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Usuario, Sistema(I)}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{El usuario identificado como socio ya puede usar la opción de comprar película (o reservarla en su defecto)}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Identificar si una persona es socia de la página web.}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El sistema solicita la identificación del usuario como socio mediante su nombre de usuario y contraseña. El sistema comprueba la vericidad de los datos sobre el socio y permite la opción deseada (compra o reserva).}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Comprobar disponibilidad} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Sistema(I)}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Primario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{Si la película está disponible para su venta en DVD, el socio ya la puede comprar. En otro caso, el socio la podrá reservar si lo desea.}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Comprobar la disponibilidad de una película para su venta en DVD.}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El usuario indica la película a consultar y el sistema comprobará su estado de disponibilidad.}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Pagar en Cuenta} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Socio(I), Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Acción por parte de un socio de hacer un pago en la cuenta corriente de la web.}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El socio notifica al sistema de que quiere realizar el pago en la cuenta, indicando la cantidad que desea ingresar y la forma de pago que usará. El sistema verificará el ingreso.}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Pagar en Metálico} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Socio(I), Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Acción por parte de un socio de pagar en metálico una cantidad determinada.}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El socio notifica al sistema de que quiere realizar el pago en metálico y el sistema le indica la cantidad a pagar.}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}

\begin{table}[ht]
\begin{tabular}{|l|l|l|l|l|l|}
\hline
\multicolumn{2}{|p{2cm}|}{Casos de uso}  & \multicolumn{3}{p{7cm}|}{Pagar con Tarjeta} & CU-x \\
\hline
\multicolumn{2}{|p{2cm}|}{Actores}       & \multicolumn{4}{p{8cm}|}{Socio(I), Sistema}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Tipo}          & \multicolumn{4}{p{8cm}|}{Secundario, Esencial}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Precondición}  & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{2}{|p{2cm}|}{Postcondición} & \multicolumn{4}{p{8cm}|}{}        \\
\hline
\multicolumn{6}{|p{10cm}|}{Proposito}                                   \\
\hline
\multicolumn{6}{|p{10cm}|}{Acción por parte de un socio de pagar con tarjeta una cantidad determinada.}                                            \\
\hline
\multicolumn{6}{|p{10cm}|}{Descripción}                                 \\
\hline
\multicolumn{6}{|p{10cm}|}{El socio notifica al sistema de que quiere realizar el pago usando una tarjeta de crédito. El sistema le indica la cantidad a pagar,la información necesaria para efectuarlo y almacena la información sobre dicho pago}                                            \\
\hline
Autor           &Elena              & Fecha    &10-11-14     &   Versión  &1.0\\
\hline
\end{tabular}
\end{table}
