# Open-World-Content-Development
Open World Content Development

## Karakter Kuralları:

- Her bir karakterin kendi klasörü vardır.
- Her bir klasör içerisinde CC4 ve Version klasörü var. 
- Model klasöründe Exported klasör içerisinde tek bir fbx olacak, bu dosya Unreal Engine da import için kullanılacak.
- Kıyafetleri Marvelous Designer de  tasarlanıp fbx olarak export edilecek
- Kıyafet fbx ler her karakterin Cloth klasöründe saklanacak

## Karakter Workflow:

CC4->MarvelousDesigner->Blender->MixamaAnimation->UE4

 İşlemler:
 
    CC4: 
           - Karakter Game base modele convert edilecek.
           - Tek bir material olacak şekilde merge işlemi uygulanacak
           - A-Pose da OBJ olarak export edilecek
    MarvelousDesigner:
            - Kıyafet giydirme işlemi yapılacak
            - Kıyafet ile birlikte karaterde exprot edilecek
    Blender:
            - Karakter ölçüsü düzenlenecek
            - Ayakkabı giydirilecek
            - Material isimleri düzenlenecek
            - FBX olarak export edilecek
    Mixama:
            - Skeleton basic(no finger) olarak yapılacak
            - Walk Animasyonu eklenecek


## Genel Kurallar:
- Model klasör içerisinde sadece bir adet Blender ve fbx olacak. Bu modellerde son hali olacaktı.
- Textures klasöründe normal textures dışında Thermal ve Damaged klasör olacak.
- Destroyed modelde kendi klasörü olacak. Klasör içerisinde 1 adet blender ve fbx olacak. Destroy texture bu klasör içerisinde olan Textures klasöründe olacaktır.
- Model triangle sayısı 100k altı olacaktır
- Model işlemi tamamlandığı zaman yeni aşamaya alınmadan önce comment bölümünde güncel resimi koyulacak. 
- Model durumu Done ise öncelik derecesi kaldırılacak

# AWS Links:
 Repos:
 
     Models:
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Models_Vehicle
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Models_Building
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Models_Character
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_UnrealEngine_Vehicle
     Maps Repo:
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_OpenWorld_GE
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/OpenWorld_Database
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Islahiye_1
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Islahiye_2
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/CV_Map_Lalapasa
        - ssh://git-codecommit.eu-north-1.amazonaws.com/v1/repos/OpenWorld_Maps
