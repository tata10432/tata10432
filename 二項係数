const ll MAX =510000;const ll MOD =1000000007;
ll fac[MAX],finv[MAX],inv[MAX];
void COMinit(){
    fac[0]=fac[1]=1;finv[0]=finv[1]=1;inv[1]=1;
    jep(i,MAX,2){fac[i]=fac[i-1]*i%MOD;inv[i]=MOD-inv[MOD%i]*(MOD/i)%MOD;finv[i]=finv[i-1]*inv[i]%MOD;}}
ll COM(ll n,ll k){if(n<k)return 0;if(n<0||k<0)return 0;return fac[n]*(finv[k]*finv[n-k]%MOD)%MOD;}
int main(){COMinit();
    
    cout<<COM(5,2)<<endl;
}
