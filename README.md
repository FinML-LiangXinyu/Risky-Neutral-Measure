# 风险中性测度

真实概率测度 $\mathbb{p}$ 下， $t$ 时刻标的股价遵循几何布朗运动 $dS_t=\mu S_tdt+\sigma S_tdW_t^\mathbb{p}$

风险中性市场中，投资者对其承担的风险不要求任何补偿，此时有股票的期望收益 $\mu$ 等于债券的无风险收益 $r$ 。故有风险中性测度 $\mathbb{Q}$ 下， $t$ 时刻标的股价遵循几何布朗运动 $dS_t=rS_tdt+\sigma S_tdW_t^\mathbb{Q}$

故有 $d{W_t}^\mathbb{Q}-d{W_t}^\mathbb{p}=\frac{\mu-r}{\sigma}dt$

等式两边在时间区间 $\left[0,T\right]$ 上取积分 $\int_{0}^{t}\left(d{W_s}^\mathbb{Q}-d{W_s}^\mathbb{p}\right)=\int_{0}^{t}{\frac{\mu-r}{\sigma}ds}$

解得 ${W_t}^\mathbb{Q}={W_t}^\mathbb{p}+\frac{\mu-r}{\sigma}t$
