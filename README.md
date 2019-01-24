# PowerShell-VM-Hyper-V-Scipt-Auto

 .\HYPERV_New-VMFromCSV -CSVPath "D:\HYPERV_VmToCreate.csv"
 
Pour récupérer le script et le fichier CSV, c'est pas ici (https://goo.gl/MVhCRw)

VMName (obligatoire) : Nom de la machine virtuelle à créer
Processors (obligatoire) : Nombre de processeurs à assigner à la machine virtuelle
VMMemoryMB (obligatoire) : Quantité de RAM à assigner à la machine virtuelle (en MB)
VHDSizeGB (obligatoire) : La taille du VHD de la machine virtuelle (en GB)
VMGeneration (obligatoire) : La génération de votre machine virtuelle (soit 1, soit 2)
VHDPath (obligatoire) : Le chemin ou sera stocké le VHD de la machine virtuelle (penser à ajouter le nom du VHD à la fin du chemin. Exemple : D:\monVHD.vhdx)
InternalvSwitchName : Nom du vSwitch interne à assigner à la machine virtuelle (ce dernier doit exister)
ExternalvSwitchName : Nom du vSwitch externe à assigner à la machine virtuelle (ce dernier doit exister)
PrivatevSwitchName : Nom du vSwitch privé à assigner à la machine virtuelle (ce dernier doit exister)
IsoPath : Chemin de l'ISO à monter dans le DVD de la machine virtuelle
