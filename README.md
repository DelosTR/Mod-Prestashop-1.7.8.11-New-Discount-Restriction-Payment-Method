 Salut, en b2b de notre côté on utilise l'escompte, un % de réduction si le client paye en comptant.
(CB ou virement) (car on a un autre module pour un paiement sous 30j)

Et pour encourager à payer direct on fait une réduction. Sauf que Prestashop ne propose pas de restriction par rapport au mode de paiement. (c'est peut être le cas avec la version 8 ou 9 j'ai pas vérifié)

J'ai testé pleins de modules, et ou ca ne marche pas, ou c'est pas fiable.

Alors je m'y suis mis, avec chatgpt5 et ca m'a pris 2 jours! Et je me suis dit pourquoi pas le partager.

Alors attention ce sont des modif core, j'ai pas fait d'override mais j'ai tout noté, et on est sur la dernière version stable 1.7 : 1.7.8.11

J'utilise un theme custom et plusieurs modules, donc si vous voulez essayer, ne le faite surtout pas en production!

En admin ca donne donc ca: (payment method selection) j'ai fais en sorte de garder le même procédé que les autres.

----

Voilà, j'espère que ca en aidera certains, perso j'aurai bien voulu avoir ca alors c'est pour ca que je partage.
On se retrouve donc avec une nouvelle restriction selon le paiement, et c'est tout, le reste c'est géré comme le truc de base.
Et dans le panier quand on passe d'un mode de paiement à l'autre ca se met à jour direct en js. 


-----------------------------------------------------------------------------------------------------------------------------------------------

 Hi, on the B2B side we use a cash/early-payment discount — a % off if the customer pays upfront (card or bank transfer), since we have another module for Net-30 payments.

To encourage immediate payment we offer a discount. The thing is, PrestaShop doesn’t provide a condition based on payment method. (Maybe in v8 or v9 — I haven’t checked.)

I tested plenty of modules and either they don’t work or they’re not reliable.

So I built it myself with ChatGPT-5 and it took me two days! Figured I’d share it.

Heads-up: these are core edits — I didn’t make an override, but I documented everything — and we’re on the latest stable 1.7: 1.7.8.11.

I’m using a custom theme and several modules, so if you want to try it, definitely don’t do it in production!

In the back office it looks like this: (payment method selection). I made sure to keep the same workflow as the other conditions.

That’s it, hope it helps some of you. Personally I wish I’d had this, so I’m sharing. You end up with a new payment-based restriction, and that’s it — the rest behaves like the stock feature. And in the cart, when you switch payment methods it updates instantly via JS. 
