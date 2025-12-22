# Appunti su Emacs

Per avviare Emacs in modalità testo usare il comando

```
emacs -nw
emacs -nw main.py
```
Per dividere in 2 la window uso

## Gestire i file

### Dividere lo schermo in orizzontale
```
C-x 2
```
### Dividere lo schermo in verticale
```
C-x 3
```

### Chiudi la finestra corrente
```
C-x o
```
### 

```
C-x 1
```
### Salvare un file

```
C-x C-s
```

### Per uscire da Emacs

```
C-x C-C
```
### Per sospendere Emacs
```
C-x C-z
```
## Spostare il point
### Spostare il point di un carattere

```
C-f 
C-b
C-n
C-p
```

### Inizio di una linea

```
C-a
```

### Fine di una riga

```
C-e
```
### Sposta di una parola

```
M-f
M-b
```

### Sposta il point al centro del testo poi all'inizio e poi alla fine ciclicamente

```
M-r
```
### Inizio e fine del buffer

```
M->
M-<

```
## sposta il point alla linea numero 
premere ALT e due volte g, verra chiesto un "go to line":
```
M-g g 
```
## il minibuffer
premendo M-x si entra nel minibuffer e emacs attede un comadno, per uscire da minibuffer premere c-g

```
M-x
C-g
```

## kill buffer

```
C-x k
```

## Copy-Paste
- la prima cosa è marcare il cursore con C-space
- poi portare il cursore nel punto in cui si dedidera copiare fino alla marcatura M-w
- portare il cursore dove si desidera inclollare C-y

## Cut-Paste
- la prima cosa è marcare il cursore con C-space
- poi portare il cursore nel punto in cui si dedidera tagliare fino alla marcatura C-w
- portare il cursore dove si desidera inclollare C-y


## Lavorare con python

### Avviare un interpete python

```
M-x run-python
M-x python-shell-send-buffer

oppure

C-c C-C
```

## Aprire una shell
```
M-x shell
```

## Undo
```
C-/
```

## Auto Complete
```
M-/
```
## Commentare una regione di codice
Prima seleziona le regione che vuoi commentare

```
M-;
```

## indentare una regione

```
C-x TAB 
```
