# pMSE
The power-law modulated multiscale entropy

Created by Kangning Xie team.


[p,beta,slope]=pMSE(mse,rmse)

% Compute the Power-law exponent modulated Multiscal Entropy (pMSE), a
% measurement of a signal's complexity.
% input: 
%        mse: the multiscale entropy of a signal. format: 1 by 20.  (use mmse.m)
%        rmse: the refined multiscale entropy of a signal. (Optional)
% output:
%        p: pMSE,1 by 20  
%        beta: the power-law exponent calculated from multiscale entropy.
% made by xie kangning, 2019.4.7
% email: kangningxie@fmmu.edu.cn; 103240963@qq.com


MATLAB code for multivariate multiscale entropy (MMSE) 
mmse.m
    Reference:
    M. U. Ahmed and D. P. Mandic, "Multivariate multiscale entropy: 
    A tool for complexity analysis of multichannel data," Physical Review 
    E, vol. 84, no. 6, pp. 061918-1 ?061918-10, 2011.
    
