## GitExtensions


GitExtensions ist eine GUI über Git, bei der es sich um eine externe Installation handelt. In Windows wird die Standard-Git-Distribution von [Git-for-Windows](https://git-scm.com/downloads) verwendet. Andere Distributionen (wie Cygwin Git) könnten funktionieren, werden jedoch nicht offiziell unterstützt. GitExtensions bis [v2.51.02](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) enthielten ein Git-Installationsprogramm.

Die minimale und empfohlene Git-Version kann von der GitExtensions-Version abhängen. Die Git-Distribution kann in bestimmten Aspekten mit GE nicht kompatibel sein, beispielsweise aufgrund geänderter Pfade und veralteter Befehle.

Für Versionen vor [v2.51.02 war](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) ein Git-Installationsprogramm enthalten, und die Git-Version wurde mit dieser Version getestet. In Version [2.51.02](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) wurde stattdessen eine Überprüfung auf die empfohlene Version aufgenommen. Allerdings musste Git aus anderen Gründen häufig aktualisiert werden, z. B. benötigt GitHub den Git 2.16 Credential Manager. Eine spätere Version sollte ebenfalls verwendbar sein. Dieses Wiki sollte nach Bestätigung aktualisiert werden. Die Versionsprüfung in der Anwendung wird nicht aktualisiert.


### Minimale Git-Version


| GitExtensions-Version | Git-Version |
| - | - |
| <= 2.51.01 | 1.7.0 |
| [2.51.02, 3.00] | 2.9.0 |
| 3.00+ | 2.22.0 |

### Empfohlene Git-Version


Empfohlene Git-Version: **2.23.0**

Sie können git von der offiziellen Website installieren:

 [https://git-scm.com/downloads](https://git-scm.com/downloads) oder mit dem [Chocolatey-Paketmanager](https://chocolatey.org/) :

```
choco upgrade -y git
```

Weitere Informationen finden Sie unter [https://chocolatey.org/packages/git](https://chocolatey.org/packages/git) .


## Diff Werkzeug


GitExtensions verwendet externe Diff-Tools, die auf dem Computer des Benutzers installiert werden müssen, um unterschiedliche Erfahrungen zu bieten und bei der Lösung von Zusammenführungskonflikten zu helfen.

Vor[v2.51.02 haben](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) wir [KDiff3](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) gebündelt, jedoch haben sich viele Benutzer für ein anderes Diff-Tool entschieden.

GitExtensions unterstützt viele verschiedene Tools. Nachstehend finden Sie eine Liste der von uns vorgeschlagenen Tools. Sie können jedoch jedes beliebige Diff-Tool installieren.


# Optionale Abhängigkeiten


## Diff / Merge-Tools


### KDiff3

Für viele [Versionen](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) vor [v2.51.02 haben](https://github.com/gitextensions/gitextensions/releases/tag/v2.51.02) wir KDiff3 gebündelt. Wenn Sie dieses Tool weiterhin verwenden möchten, empfehlen wir Ihnen, den [Chocolatey-Paketmanager](https://chocolatey.org/) zu verwenden, um es zu installieren:

```
choco upgrade -y kdiff3
```

Weitere Informationen finden Sie unter [https://chocolatey.org/packages/kdiff3](https://chocolatey.org/packages/kdiff3) .

### P4Merge

P4Merge ist bei Benutzern sehr beliebt. Wir empfehlen Ihnen, den [Chocolatey-Paketmanager](https://chocolatey.org/) zu verwenden, um ihn zu installieren:

```
choco upgrade -y p4merge
```

Weitere Informationen finden Sie unter [https://chocolatey.org/packages/p4merge](https://chocolatey.org/packages/p4merge) .
