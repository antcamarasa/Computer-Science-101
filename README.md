# Computer Science 101 
The ultimate guide to computer science.

## Milestone 1 : Computer Architecture
### 🔹 Ce qu’il faut absolument connaître :
- Logique numérique et portes logiques (AND, OR, NOT, NAND, etc.)
- Conception d’un processeur simple (ALU, registres, instructions de base)
- Langage Assembleur (traduction des instructions, registre, pile)
- Mémoire et hiérarchie mémoire (cache, RAM, mémoire virtuelle)

| Mois    |  Ressources                   | Compétences                   
|---------|-------------------------------|-----------------------------------------------------------------------------|
| 1       | From Nand To Tetris           | Logique numérique, conception de processeur, assembleur, mémoire et registres
| 2       | CS : APP                      | Chapitres sur Mémoire & Processus
| 2       | MIT Computation Structure     |   

### 🛠 Projet Final de la milestone 1 :
✅ Construire un processeur simple (From Nand to Tetris).
✅ Écrire et exécuter un programme en assembleur.

### 🛑 Ce que tu peux laisser de côté pour plus tard :
❌ Détails avancés sur les caches et pipeline CPU.
❌ Conception détaillée de microarchitectures complexes.
❌ Systèmes de fichiers et gestion avancée des processus (mieux abordés en Mois 2).

## Milestone 2 : Operating System 
### 🔹 Ce qu’il faut absolument connaître :
- Processus et planification (création, états d’un processus, ordonnancement)
- Gestion de la mémoire (pagination, segmentation, mémoire virtuelle, allocation mémoire)
- Appels système et interaction avec le noyau (fork, exec, system calls, context switching)
- Systèmes de fichiers (bases uniquement) (blocs, inodes, accès aux fichiers, ext4 en surface)
- Threads & Synchronisation (pthreads, mutex, sémaphores, conditions de course)

| Mois    |  Ressources                           | Compétences                   
|---------|---------------------------------------|---------------------------------------------------------------------------------------------------------------|
| 1       | Operating system : Three easy pieces  | Gestion mémoire, processus, système de fichiers, appels système, planification
| 2       | MIT 6 S081                            | Cours clé : Processus et appels système, Mémoire virtuelle et gestion mémoire, planification et synchronisation
| 3       | XV6                                   | Permet de voir un OS simple en pratique et de comprendre son code.
| 4       | *                                     |  

### 🛠 Projet Final du Mois 2 :
✅ Modifier xv6 pour ajouter une fonctionnalité (ex: planification round-robin améliorée).
✅ Écrire un programme en C qui interagit avec le noyau via les appels système.

### 🛑 Ce que tu peux laisser de côté pour plus tard :
❌ Détails avancés sur les systèmes de fichiers (B-Trees, journaling) → Mieux en Mois 6 (Bases de données).
❌ Sécurité avancée (buffer overflow, exploitation mémoire) → Mieux après avoir une bonne base en OS.
❌ Concurrence avancée et scheduling multi-threading (Threads, Locks) → Mieux en Mois 3 (Réseaux et multi-threading).

## Mileston 3 : Networks
### 🔹 Ce qu’il faut absolument connaître :
- Modèle OSI et TCP/IP (couches réseau, transport, application)
- Sockets et communication réseau (TCP, UDP, création de sockets en C)
- Protocoles réseau majeurs (HTTP, DNS, TLS, SSH, WebSockets, etc.)
- Analyse des paquets (Wireshark, lecture de trames réseau, entêtes IP/TCP/UDP)
- Notions de performance et d’optimisation réseau (latence, congestion, multiplexage, proxies, CDNs)

    Multi-threading et concurrence appliquée aux réseaux (serveurs multi-threadés, locks, parallelisme, non-blocking I/O)
| Mois    |  Ressources                                          | Compétences                   
|---------|------------------------------------------------------|-------------------------------------------------------------------------------------|
| 1       | Computer networking a top down approach              | Sockets, TCP/IP, HTTP, analyse de paquets, gestion des connexions
| 2       | CS 340 Intro to Computer networking                  | Contient des TP sur les sockets, la programmation réseau en C et les protocoles TCP/UDP.
| 3       | Beej's Guide to Network Programming (Sockets en C)   | Apprentissage pratique des sockets et de la communication client-serveur en C.
| 4       | Wireshark pour l’analyse de paquets                  | Le trafic réseau et les interactions HTTP/TCP en temps réel.

### 🛠 Projet Final du Mois 3 :
✅ Créer un serveur HTTP minimaliste en C (serveur socket qui gère plusieurs connexions avec des threads).
✅ Capturer et analyser le trafic réseau avec Wireshark (ex: voir une requête HTTP complète).
✅ Implémenter un client TCP et UDP en C pour comprendre la gestion des connexions.

### 🛑 Ce que tu peux laisser de côté pour plus tard :
❌ Compression (Huffman, zlib, gzip) → Mieux en Mois 4 (Systèmes & fichiers avancés).
❌ Routage avancé (BGP, OSPF, etc.) → Mieux si tu fais du DevOps/réseau plus tard.
❌ Sécurité réseau avancée (exploitation réseau, MITM, attaque DNS) → Mieux après une solide base en OS & Réseau.

## Milestone 4 : Algo & Data structures

## Milesone 5 : Compilateurs & interprèteurs
### 🔹 Ce qu’il faut absolument connaître :
- Comment fonctionne un compilateur ? (lexing, parsing, AST, génération de code, optimisation)
- Différences entre interpréteur et compilateur (exécution directe vs génération de code machine)
- Concepts fondamentaux du parsing (grammaires, LL/LR parsing, générateurs comme ANTLR/Bison)
- Notions de machine virtuelle et bytecode (ex: Python, JVM, WebAssembly)
- Programmation fonctionnelle (utile pour l’implémentation des langages et les interpréteurs récursifs)

| Mois    |  Ressources                                          | Compétences                   
|---------|------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| 1       | Stanford Compilers                                   | Approche académique et structurée sur la compilation, avec exercices et TP.
| 2       | Crafting interpreteurs                               | Explication progressive pour implémenter un interpréteur en Java et C.
| 3       | Programmation fonctionnelle Haskell                  | Les interpréteurs utilisent souvent des concepts de récursion, arbres syntaxiques et evaluation différée.

### 🛠 Projet Final du Mois 5 :
✅ Créer un interpréteur minimaliste (ex: mini langage type LISP ou Python-like).
✅ Coder un compilateur simple vers bytecode (ex: générer un fichier exécutable à partir d’un code source simple).
