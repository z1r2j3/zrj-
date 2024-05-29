/*C++:
关于vector容器
vector v()//调用无参构造函数
vector v1(v2)=====v1=v2;
可设置一个print(vector &v)打印函数
print{for(vector<int>::iterator it=v.begin();it!=v.end();it++)
      {cout<<*it<<endl;}
      }
###/////2 /////
    vector<T>v;
    v.push_back();//对于尾部插入v.pop_back()//尾部删除v.insert(iterator//迭代器例如v.begin(),(n),ele)
    v.erase(iterator1(,iterator2))//提供一个迭代器或者迭代器区间
    v.clear()====v.erase(v.begin(),v.end())
    v1=v2/assign();
    v.empty()/v.capacity()/v.size()/v.resize();

当v中有数据时，需访问元素时----
v[i]/v.at(i);
v.front()第一个元素   v.back()最后一个元素  v.swap////vector<int>(v).swap(v)根据v当前size进行拷贝与交换，交换后进行内存清除*/
