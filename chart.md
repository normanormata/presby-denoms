# Presbyterian Denominational History Chart

```mermaid
  flowchart LR
  
  %% Denoms,Sides,Synods, etc.
    AP[Associate<br>Presbytery]
    ARPC[Associate<br>Reformed<br>Presbyterian<br>Church]
    ARSS[Associate<br>Reformed<br>Synod of<br>the South]
    ASNA[Associate Synod<br>of North America]
    BPC[Bible<br>Presbyterian<br>Church]
    CCPC[Colored\2nd<br>Cumberland<br>Presbyterian<br>Church]
    CMC[Calvinistic<br>Methodist<br>Church in<br>the U.S.A.]
    COS[Church of<br>Scotland<br>1690]
    CP[Cumberland<br>Presbytery]
    CPC[Cumberland<br>Presbyterian<br>Church]
    CS[Cumberland<br>Synod]
    EPC[Evangelical<br>Presbyterian<br>Church]
    FP[First<br>Presbytery<br>1706]
    FPC[Free<br>Presbyterian<br>Church]
    NL[New Light<br>Reformed<br>Presbyterian<br>Church General<br>Synod]
    NS[New Side]
    NSC[New School]
    OL[Old Light<br>Synod of the<br>Reformed<br>Presbyterian<br>Church of<br>North America]
    OPC[Orthodox<br>Presbyterian<br>Church]
    OS[Old Side]
    OSC[Old School]
    PCA[Presbyterian<br>Church in<br>America]
    PCCSA[Presbyterian<br>Church in the<br>Confederate<br>States of<br>America]
    PCUS[Presbyterian<br>Church in the<br>U.S.]
    PCUSA[Presbyterian<br>Church in the<br>U.S.A.]
    PUSA[Presbyterian<br>Church<br>U.S.A.]
    RP[Reformed<br>Presbytery]
    %%RPCNA[Reformed<br>Presbyterian<br>Church in<br>North America]
    RPES[Reformed<br>Presbyterian<br>Evangelical<br>Synod]
    %%RSNA[Reformed<br>Synod of<br>North<br>America]
    SNYP[Synod of<br>NY & PA]
    UPCNA[The United<br>Presbyterian<br>Church of<br>North America]
    UPCUSA[United<br>Presbyterian<br>Church in the<br>U.S.A.]
    USS[United<br>Synod of<br>the South]
    WMC[Welsh<br>Methodist<br>Church<br>1750]
    ECO[A Covenant<br>Order of<br>Evangelical<br>Presbyterians]
  
  %% Flow
    FP-->|1741| OS & NS
    COS-->|1753| AP
    OS & NS -->|1758| SNYP
    COS-->|1774|RP
    AP & RP-->|1782| ARPC
    SNYP-->|1789|PCUSA
    AP-->|1782| ASNA
    PCUSA-->|1810| CP
    CP-->|1813| CS
    ARPC-->|1821| ARSS
    CS-->|1829|CPC
    RP-->|1833| OL & NL
    PCUSA-->|1837| OSC & NSC
    OSC & NSC-->|1847| FPC
    ARPC & ASNA-->|1858| UPCNA
    NSC-->|1858|USS
    OSC & NSC-->|1861|PCCSA
    FPC-->|1863| PCUSA
    USS-->|1864| PCCSA
    PCCSA-->|1865| PCUS
    WMC-->|1869| CMC
    OSC & NSC-->|1869| PCUSA
    CPC-->|1874|CCPC
    CMC-->|1920| PCUSA
    PCUSA-->|1936| OPC
    OPC-->|1938| BPC
    UPCNA-->|1958| PCUSA
    BPC-->|1956| EPC
    EPC & NL-->|1965| RPES
    UPCNA & PCUSA-->|1958| UPCUSA
    ASNA-->|1969|OL
    PCUSA-->|1973| PCA
    UPCUSA-->|1981| EPC
    RPES-->|1982| PCA
    PCUS & UPCUSA-->|1983| PUSA
    PUSA-->|2012| ECO
    %%OPC-.->|present| Z(Continuing)
    %%BPC-.->|present|Z
    %%CPC-.->|present|Z
    %%CCPC-.->|present|Z
    %%PUSA-.->|present|Z
    %%ARSS-.->|present|Z
    %%OL-.->|present|Z
    click OPC "https://opc.org/" "This is a link" _blank
