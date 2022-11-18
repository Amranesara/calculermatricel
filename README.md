# calculermatricel
x=[75.6 74.3 75.3 72.7 83.7 75.8 83.4 81 54.5 53.3 58.2 62.9 65.7 70.5]
n=length(x);

disp('%%%%%%%% moyenne %%%%%%%%%%%%%%')
%%  (b-1) calcule de xbar  à l'aide de la fonction moy
xbar=moy(x,n);
disp(['la valeur de xbar à l''aide de la fonction moy est',num2str(xbar)])
va=variance(x,n);
s=sqrt(va);
disp(['la valeur de l''écart-type à l''aide de la fonction variance est:',num2str(s)])
