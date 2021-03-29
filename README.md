# Doações
<table>
    <tr>
        <td> <!-- PagSeguro -->
            <h3>
                <div align="center">PagSeguro</div>
            </h3>
            <a href="https://pag.ae/bljJm47"><img src="https://stc.pagseguro.uol.com.br/public/img/botoes/doacoes/120x53-doar.gif"></a>
        </td>
        <td> <!-- PayPal -->
            <h3>
                <div align="center">PayPal</div></h3>
            <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=7VVS675TLJHUL&lc=BR&item_name=Eracydes%20Lima%20Carvalho%20Junior&currency_code=BRL&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif"></a>
        </td>
        <td> <!-- PicPay -->
            <h3>
                <div align="center">PicPay</div></h3>
            <a href="http://picpay.me/sansaoipb"><img src="https://lh3.googleusercontent.com/PX1pBd24_ygdLwvKMFrnUhJqGzG-YmhbYPkE8FM74qdXc-na7EqIA808F-7WAjZnvjziEESYZz2n8Ofn6WGdTrRufae_A7WbEVA5xASAUDpWNyqcVKE0GKNJrEVMBLCee5evEdrgJn8PgaI0E7qr0QDf6lTuCHI9osuziJwJ8-OTiR1JMOWLPLrw-wOW7IZ3DQCkyQECZpb_123x1K1fKNRw6cIyEWSgYRVwzX3PeljmxyH-EBOF-1wrO67-4rLP0CfbpRxJaX3pMyNlFZMLD0R6k6HvL1ax328z0qLafMwHjLPFlVEcyMkl-CFwJN9vgP37plpZ76NNruCBkj6W-MKQkvLevjcjf-Zq718N7ow8ZSlvUOCCZFJ1ieZZrLOINaMsmYGqMYpGEMME910zzAKtd-dm0IJ0TQTx_pZ0BXniK0HCvVhNHhPiYNYJGBMv_wlakLQ8XIcBdi0iIaEOFvrGSHhXEbDx6OZ9EKsvXQNoKBRwXD0Nnqxf3o-HW0U-P3pAskj3GSBa9qfvQqK-P4pxG98hYJ4st7_FA655I9n5bP-E6lIgFqvdJC8odyVfXFpHtVWfaO9_WVXowqdiXKzX9qQ9PetQNhTnJG_WgoqocmIh1FJhAYd08fonFfbmS_Hhnvi5qqxQytCqYxqWfh1elL18X8c=w120-h53-no"></a>
        </td>
    </tr>
</table>

# DownDetector para Zabbix e Grafana
Scrapper para serviços no DownDetector <br>

# Requisitos:
Ter instalado Python 3.6 (ou superior)<br><br>

<h3>
Instale os pacotes:
</h3>
<pre>python3 -m pip install --ignore-installed cloudscraper scrapy "PyYAML>=5.1"</pre>


# Zabbix:

<b>OBS:</b><br>
Existe um local padrão onde fica os scripts, que tem 2 locais possiveis dependendo da forma de instalação do ZABBIX, 
compilando (<code>/usr/local/share/zabbix/externalscripts/</code>) ou por pacote (<code>/usr/lib/zabbix/externalscripts/</code>), respectivamente.<br>

Acesse o local existente e adicione o script <code>dd.discovery</code>, e execute os comandos:

<pre>chown zabbix. dd.discovery ; chmod +x dd.discovery</pre>

<!--

<h3>
Template:
</h3>
Aguarde, será disponibilizado em breve
<br><br>


<h3>
Dashboard Grafana:
</h3>

Aguarde, será disponibilizado em breve
-->

<h3>
Template e Dashboard Grafana no curso abaixo:
</h3>
https://formulamonitoramentozabbix.com.br/cursosgratuitos