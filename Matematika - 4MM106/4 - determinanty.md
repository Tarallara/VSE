<h1>Determinanty</h1>

<h2>V1 existuje a jednoznacnosti incerzni matice </h2>
    a je regularni <=> existuje A^-1 a je urcena jednoznacne

<h2>V2 - o navzájem inverzních maticích </h2>
    je-li matice A regulárnní, pak A^-1  = A
    D;sledek : AA^-1 = A^-1 A  = J

<h2>V3 - o maticové rovnici</h2>
    JE-li A regulární matice řádu n, platí:
    (i) rovnice AX = B ma jedine reseni X = A^-1 B proto B typu nxp,
    (ii) rovnice AX = B ma jedine reseni X B * A ^-1 proto B typu qxn

     pozn
    řešte maticovou rovnici XA - B = 3X pro
     A =  | 4 1 |   B = | 2 1 |
          | 3 5 |       | 1 1 |
          XA - B = 3X 
          XA - 3X = B
        X(A-3J) = B
        X = B (A-3J)^-1

pozn 
    (i) v případě, že atice A = V3 není regulární, nelze vyloučit existenci řešení rovnice. hledá se převod na soustavu lineárních rovnic
    (ii) naopak každou soustavu LR lze reprezentoavt maticovou rovnicí Ax=b, kde A je matice soustavy b sloupce pravích stran,
        x sloupec neznámých. TO umožnuje využit V3 pro řešení soustavy pomocí inverzních matic - viz V4

<h2>V2 - o řešení soustavy LP pomocí inverzní matice</h2>
    je-li A matice soustavy LR regulární, pak soustavy zapsané ve tvaru Ax = b má jediné řešení X A^-1, b

pozn. použití malých písmenek x, b pro matice 
    - povolená výjímka - značí sloupcové vektory 

    Př. pomocí matice řešte soustavu    
        2x^1 + 5x^2 = 7
        x^1 + 3x^2 = 5 