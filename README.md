# First-React-Native

React-Native ile Klavye

Keyboard ( Klavye )
Klavye olaylarını kontrol eden bir modül. Kullanımı ise oldukça basittir. Klavye olay ve durumlarında değişiklik yapmamıza olanak sağlar.

Methodlar;
AddListener( )
RemoveListener( )
RemoveAllListener( )
Dismiss( )
ScheduleLayoutAnimation
AddListener( ) :
static addListener(eventName, callback)

Javascript fonksiyonu tanımlanmış bildirim olayına bakar. İki parametre alır bunlar;

Parametreler;
eventName = String, Olayın tanımlandığı bölge.
Callback = function, Olay tetiklendiğinde çağırılacak fonksiyon.
EventName;
keyboardWillShow
keyboardDidShow
keyboardWillHide
keyboardDidHide
keyboardWillChangeFrame
keyboardDidChangeFrame
RemoveListener( ):
static removeListener(eventName, callback)

Dinleyiciyi kaldırır.

Parametreler;
EventName = String, Required(yes)
Callback = function, Required(yes)
RemoveAllListener( ):
static removeAllListeners(eventName)

Belirli bir olay türü için tüm dinleyicileri kaldırır.

Parametre;
EventType = String, Required(yes)
Dismis( ):
static dismiss()

Etkin klavyeyi kapatır ve odağı kaldırır.

ScheduleLayoutAnimation:
static scheduleLayoutAnimation(event)

Konum değişikliklerinin TextInput (veya diğer klavye aksesuar görünümü) boyutunu klavye hareketleriyle senkronize etmek için kullanışlıdır.

