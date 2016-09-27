```python
a = "Mourin Mirza"
a[::-1]

### Basic of slice notation
### example02 -------------------
## start (with positive integers)
print 'coup_ate_grouping'[0]  ## => 'c'
print 'coup_ate_grouping'[1]  ## => 'o' 
print 'coup_ate_grouping'[2]  ## => 'u' 

## start (with negative integers)
print 'coup_ate_grouping'[-1]  ## => 'g'
print 'coup_ate_grouping'[-2]  ## => 'n' 
print 'coup_ate_grouping'[-3]  ## => 'i' 

## start:end 
print 'coup_ate_grouping'[0:4]    ## => 'coup'    
print 'coup_ate_grouping'[4:8]    ## => '_ate'    
print 'coup_ate_grouping'[8:12]   ## => '_gro'    

## start:end 
print 'coup_ate_grouping'[-4:]    ## => 'ping' (counter-intuitive)
print 'coup_ate_grouping'[-4:-1]  ## => 'pin'
print 'coup_ate_grouping'[-4:-2]  ## => 'pi'
print 'coup_ate_grouping'[-4:-3]  ## => 'p'
print 'coup_ate_grouping'[-4:-4]  ## => ''
print 'coup_ate_grouping'[0:-1]   ## => 'coup_ate_groupin'
print 'coup_ate_grouping'[0:]     ## => 'coup_ate_grouping' (counter-intuitive)

## start:end:step (or stop:end:stride)
print 'coup_ate_grouping'[-1::1]  ## => 'g'   
print 'coup_ate_grouping'[-1::-1] ## => 'gnipuorg_eta_puoc'

## combinations
print 'coup_ate_grouping'[-1::-1][-4:] ## => 'puoc'
```
