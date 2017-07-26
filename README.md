# wai-not-a-category
WAI has some really nice categorical properties . This library allows you to use those

## Properties

```
Functor f => Profunctor (ApplicationT f)
Functor m => Strong (ApplicationT m)
Traversable f => Cochoice (ApplicationT f)
Applicative f => Choice (ApplicationT f)
Distributive f => Closed (ApplicationT f)
Applicative m => Traversing (ApplicationT m)
(Applicative m, Distributive m) => Mapping (ApplicationT m) 
Functor f => Representable (ApplicationT f)
Functor f => Sieve (ApplicationT f) f 
Monad f => Monad (ApplicationT f a) 
Functor f => Functor (ApplicationT f a)
Applicative f => Applicative (ApplicationT f a)
Alternative f => Alternative (ApplicationT f a)
MonadPlus f => MonadPlus (ApplicationT f a)
Distributive f => Distributive (ApplicationT f a)
type Rep (ApplicationT f)
Monad f => MonadReader a (ApplicationT f a)
```
	 
